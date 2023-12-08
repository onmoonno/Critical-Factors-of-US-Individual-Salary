# Critical Factors of US Individual Salary
Data Visualization Portfolio: The primary goal of this project was to provide data-driven insights for the UVW marketing team to help them better understand their target market and support them in making informed decisions. Various exploratory data analysis methods were used to analyze the relationship between variables and locate the critical factors affecting individual salaries.


## Code and Resources Used 
**Software:**  Python 3.11, Google Colaboratory

**Packages:** pandas, numpy, matplotlib, seaborn, scipy, sklearn, statsmodels.graphics.mosaicplot

**DataBase:** extracted by Ronny Kohavi and Barry Becker from the 1994 United States Census database

**Project Source:** Arizona State University, CSE 578 Data Visualization Portfolio

## Technique assumptions and data cleaning
* Technique Assumptions: The dataset for analysis was extracted by Ronny Kohavi and Barry Becker from the 1994 United States Census database and modified for study, which was assumed to be accurate, complete, and with no bias on all the attributes. The data were considered to collect without bias from a representative sample of the target population, which can be represented to the public.

*	Data Cleaning:  
    * clean out the duplicates  
    * replace “?” with nan  
    * drop the column “Fnlwgt”  

## Data Overview and Interested Features:
For data overview, univariate analysis was performed to get a basic idea about whether each attribute's value significantly influences the income of 50K per year. The numerical attributes were analyzed and presented by line charts and boxplots. The other categorical attributes were analyzed and depicted mainly by the bar charts and pie charts. Before visualization, some data in attributes were normalized to show the underlying trend. The Analysed features include: 
*	Age
*	Work class
*	Education
*	Education-num
*	Marital status
*	Occupation
*	Relationship
*	Race
*	Sex
*	Capital gain
*	Capital loss
*	Hours per week
*	Native Country
*	Income
  
## EDA 
1. As shown in Fig. 1, Education is a strong indicator of income. After sorting the normalized data according to the education-num, positive trends showed that the higher the education level, the better chance people have to earn 50k per year. For example, more than 50% of people who own a graduate degree (master's or higher) earn more than 50K per year. On the other hand, less than 20% of people who only finished high school or lower can have that same compensation.

![alt text](https://github.com/onmoonno/Critical-Factors-of-US-Individual-Salary/blob/main/figure1.png)

2. As the data points are dispersed evenly across the plot, the scatter plot didn’t show a clear correlation between age and income. (As shown in Fig. 2) However, some clustering patterns did reveal by the different hues. As shown in the density plot, the majority of people whose salary more than 50K per year fall into the age group of 30 to 60 years old, education level of 10 (some college) or higher and work hours longer than 40 hours per week. The same conclusion can be obtained from a univariate analysis of each attribute in the appendix. Thus, people younger than 30 years old, with an education level of high school or lower, and working less than 40 hours a week may hardly earn more than 50K per year. A mosaic plot shows that as the education level gets higher, the proportion of >40 hours gets more extensive, which means people with higher education levels generally work longer. Simultaneously, the proportion of people earning >50K is getting more prominent along with the first trend, which indicates that people who own a master's or doctorate and work longer than 40 hours per year hold a better chance of earning higher than 50K per year. On the other hand, people who own a level of education before high school and work less than 40 hours per week strongly indicate having a salary of less than 50K per year.
![alt text](https://github.com/onmoonno/Critical-Factors-of-US-Individual-Salary/blob/main/figure2.png)

3. As shown in Fig. 3, capital is a good indicator of income level. The higher the education levels tend to earn more than 50K per year. People with no capital and an education level under 10 have more chances of making less than 50K per year.
![alt text](https://github.com/onmoonno/Critical-Factors-of-US-Individual-Salary/blob/main/figure3.png)

4. The relationship is a strong indicator of income. Significant different patterns were shown in the mosaic plot in Fig. 4. People who are married hold a better chance of earning a high salary; others are not. Univariate analysis shows that two-thirds of the population are males, and onethird are female. However, the female population is skewed to younger females who are unmarried or not in the family. Males are, on the contrary. That’s why females have a lower chance of earning a high salary. Husbands and wives are much better at making more than 50K per year than others. Own child or other relative are strong indicators of having a salary less than 50K per year. In conclusion, unmarried is a strong indicator of wages less than 50K, especially for females.
![alt text](https://github.com/onmoonno/Critical-Factors-of-US-Individual-Salary/blob/main/figure4.png)

5. Occupation is a strong indicator of income. As shown in Fig. 5, different occupation offers a significantly different chance of getting good pay. For example, over 40 percent of people working as executive managerial and professional specialty own more than 50K annually. However, other occupations, such as private house service, other services, handler cleansers, etc., can hardly hold more than 50K per year.People with a higher education level and occupations such as professional specialty, executive managerial, sales, etc., have a better chance of earning more than 50K per year. On the other hand, people whose education level is below nine and who work in the armed force or private housing services can hardly get more than 50K per year. Therefore, occupation combined with education can be a strong indicator of salary.
![alt text](https://github.com/onmoonno/Critical-Factors-of-US-Individual-Salary/blob/main/figure5.png)

