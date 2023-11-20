PLEASE FIND ATTACHED THE FOLLOWING FILES
first_question - SV: answers the first question.
retirement_analysis - BN: co answers the second question.
Retirement Analysis - GD: co answers the second question.

PRES Retirement Analysis: Group presentation slides.

PLEASE FIND ATTACHED THE FOLLOWING FOLDERS
data: contains spreadsheets used for the investigation
--------------------------------

# Project1_Group4
First Group Project

##  Overview
The objective of this analysis is to investigate whether specific professions exhibit an inclination for early retirement and what factors influence it. By examining retirement age data across various professions, we aim to identify any patterns, trends that suggest a correlation between a person's occupation and the age at which they retire. This analysis seeks to provide insights into the retirement landscape across different professions and contribute to a better understanding of retirement patterns in the workforce.
#Data Source
https://www.abs.gov.au/statistics/labour/employment-and-unemployment/retirement-and-retirement-intentions-australia/2020-21#data-downloads

Tables used to answer question from link
Question 1: Table 4- 'Previous jobs of retirees', Table 13 - 'Populations of states & territory'
Question 2: Table 3 - 'Characteristics of Retirees'

Hypothesis:
We believe the main reasons for retirement at a younger age is consistent numerous factors such as; financial success within household, physical capabilities for their respective field & how dependant they are by defacto members. We also believe the age of retirement well prove to be less consistent overtime as there is more opportunity for success in certail fields of work.

The 3 Questions:
-Question 1: Do certain professions retire at an earlier age?
-Question 2: What factors influence early retirement?
-Question 3: How has retirement age changed overtime for everyone?

Assignments for members:
Swapna: Question 1 (all)
Gayan: Question 2 (factors including: super contribution & reasons for retiring)
Braydon: Question 2 (initial data cleaning of 'Characteristics of Retirees.xlsx' file & pre-retirement income factor).
Julia: Question 3 (dropped) 

# Retirement Analysis: 
Do certain professions retire at an earlier age? What factors influence early retirement?
 How has retirement age changed overtime for everyone?


CONTENT WITHIN 'first_question_SV'
------------------------------------
 ## prerequisites
To produce this analysis, we will need the following tools and libraries:
Python Pandas NumPy Jupyter Notebook Matplotlib
The project involves several tasks:
# Table of contents:
1.	Preparing the Data
2.	Generate Summary Statistics and Obersvations
3.	Created Bar Charts
4.	A Line Plot 
5.	Results



# Tasks
Our project team divided our tasks in to three parts:
Do certain professions retire at an earlier age? 
What factors influence early retirement?
How has retirement age changed overtime for everyone?

First Task:
#  Do certain professions retire at an earlier age?
## Data overview:
## Preparing Data:
We cleaned data to desired data frame by using python code.
The main Data set is read from excel file (Previous jobs of retirees - cleaned.xlsx)   is     retiries _df  consist of  Cleaned data set  includes variables , Year, Population of interest , age at different intervals ,Average age, Classification ,Category.
Image: retirees Data set.
![image](https://github.com/braydonnugent/Project1_Group4/assets/136966712/7817db00-0b4e-4930-8037-796298b2a66c)

 

Identify a statistical relationship or connection between two variables i.e. the type of profession and the retirement age.
**Specific Professions: ** The question is focused on particular occupations. It suggests exploring whether individuals in certain fields tend to retire earlier than those in other professions. Evaluate variable Category , find lists of last jobs in variable Classification and group them .
**Earlier Retirement Ages:** The primary focus is on the timing of retirement.  Determine if there's a tendency  for individuals in certain professions to retire at a younger age compared to different fields.
 **Implication:** The question implies that there might be a pattern or trend, and the analysis will involve examining data to identify if such a correlation exists.
  
### Observations:
Average(calculated using mean) age in all different professions:

 ![image](https://github.com/braydonnugent/Project1_Group4/assets/136966712/cb40c774-c757-44e7-a10d-6345025dc27e)

**Early Retirement Industries:**- Categories such as Financial and insurance services, Electricity, gas, water and waste services, and Mining have notably lower average ages at retirement, suggesting that individuals in these industries tend to retire relatively early. i.e. at average age 48.16 and 48.83 .
**Mid-Range Retirement Ages:**  -Categories like "Manufacturing," "Wholesale trade," and "Arts and recreation services" fall in the mid-range of average retirement age falls under 52.9 to 54.8
 **Later Retirement Industries:** - Professions such as Professional, scientific and technical services, Transport, postal and warehousing, and Education and training have higher average ages at retirement, indicating a tendency for later retirement in these sectors .i.e. average age falls in  60.8 to 62.1

**Explore patterns**
   - Investigate potential patterns influencing retirement age and  decisions by calculating mean and median over  all years(2014-2021)

Graph shows mean age values:
 
![image](https://github.com/braydonnugent/Project1_Group4/assets/136966712/3b1d51b3-f502-4120-96f2-b933afa020b6)


Graph shows median age:
![image](https://github.com/braydonnugent/Project1_Group4/assets/136966712/852946b9-1e8a-4ea0-9207-2c3f5c849f04)

**Median** 
The lowest median values of average age for all categories are in the range of 57 to 58 years. 
 . Administrative and support services (57.4865)
 . Accommodation and food services (57.6080)
 . Financial and insurance services (57.7515)
 . Retail trade (57.8765)
 Highest Average Retirement Age: are in the range of 60 to 61 years. These include:
 . Professional, scientific and technical services (61.3350)
 . Agriculture, forestry and fishing (61.4775)
 . Construction (60.7455)
 . Transport, postal and warehousing (60.6655)
 Mid-Range Average Retirement Age: (around 59 years) include:- Other services (59.4330)- Public administration and saf
 . Health care and social assistance (59.6700)
 . Wholesale trade (59.7155)ety (59.6490)
 . Electricity, gas, water and waste services (59.7920)


** Exploring median average age and related years**
**Graph showing top 5 Median average age values by profession and in different  years :**  
![image](https://github.com/braydonnugent/Project1_Group4/assets/136966712/fa3334fb-9b96-4c2d-8d9b-03283d3b25d8)

1. **Accommodation and Food Services:**
   . The average age at retirement for this profession increased from 55.76 in 2014-15 to 58.73 in 2020-21. There's a general upward trend in retirement age over the years.

2. **Administrative and Support Services:**
   . The average age at retirement for this profession increased from 55.83 in 2014-15 to 60.37 in 2020-21. Similar to the previous profession, there's a noticeable increase in retirement age over the years.

3. **Financial and Insurance Services:**
   . The average age at retirement fluctuates over the years but generally increased from 57.50 in 2014-15 to 59.70 in 2020-21.

4. **Manufacturing:**
   . The average age at retirement for the Manufacturing profession increased from 58.12 in 2014-15 to 59.84 in 2020-21. There's a slight upward trend in retirement age.

5. **Retail Trade:**
   . The average age at retirement for Retail Trade fluctuates, with a decrease from 59.03 in 2018-19 to 57.32 in 2020-21. There's a notable decrease in retirement age in the most recent years
   . Across the professions, there seems to be an overall trend of increasing retirement ages over the years.
**Variability:** - There's variability in retirement ages within each profession, and the reasons for this variability would require further investigation.
 **Year-to-Year Changes:** - Some professions exhibit consistent increases in retirement age over the years, while others show fluctuations or occasional decreases.

 #  comparative Analysis 
. **Comparative Analysis:**
   - Monitor the data over time to identify any emerging trends or shifts in retirement patterns within these industries.Compare these average retirement ages in two different years 2018-19 and 2020-21
   - ![image](https://github.com/braydonnugent/Project1_Group4/assets/136966712/96c705ad-a083-4b03-80dc-f94d9e23c362)

 
 **Overall Change in Average Age:**
   . In general, there seems to be an increase in the average age at retirement from the year 2018-19 to 2020-21 for many categories.
 **Highest Average Age at Retirement:**
   . "Professional, scientific and technical services" has consistently shown one of the highest average ages at retirement in both 2018-19 (62.056750) and 2020-21 (62.892875).
**Lowest Average Age at Retirement:**
 . In 2018-19, "Electricity, gas, water and waste services" had the lowest average age at retirement (43.456625), while in 2020-21, "Agriculture, forestry and fishing" had the lowest (46.700000).
**Noticeable Changes:**-Some categories experienced significant changes in average age at retirement over the two years. For example, "Construction" increased from 60.1to 62.5
**Consistency in Some Categories:**
  Categories like "Health care and social assistance," "Retail trade," and "Manufacturing" show relatively consistent average ages at retirement over the two years
Overall ,There are noticeable differences in average ages at retirement between different categories, highlighting potential sectors.Consider external factors that might have influenced the changes in retirement ages, such as economic conditions, industry trends, or policy adjustments.Electricity, gas, water and waste services" in 2018-19 and "Agriculture, forestry and fishing" in 2020-21 have average ages that stand out. Investigate if these values are outliers or if there are specific reasons for the differences


# RESULTS/ANALYSIS:
In conclusion, our analysis of average retirement ages reveals distinct patterns across professions. Industries such as Financial and insurance services,Electricity, gas, water and waste services, and Mining exhibit a consistent trend of early retirements. So, it means some of professions retire early compared to other professions. 
Understanding these patterns is crucial for employers, policymakers, and individuals planning for their retirement. Further research, behind these trends and effecting factors can provide information to make future decisions.


About
-These projects were completed as part of Data Analysis Bootcamp.
Contact
If there are any questions or concerns, I can be reached at:
github: svuth23
[email: swapna.vuthpala@gmail.com]
-----------------------------------------------------------------

CONTENTS WITHIN 'retirement_analysis - BN.ipynb'
-----------------------------------------------

# Second Task:

Question:
What factors influence early retirement?
Plots:

generalised_df Data Frame Head & Code Screenshot: demonstration of data cleaning & example of commonly used data frame.
<img width="785" alt="image" src="https://github.com/braydonnugent/Project1_Group4/assets/142812919/688be0ac-bdbb-4c02-8eff-d98f8a066793">

Bar Charts comparing pre_retirement income across age ranges (2020-21) 
![image](https://github.com/braydonnugent/Project1_Group4/assets/142812919/47f11d8d-2440-41ea-b985-68de879b7578)

Pie Charts comparing overall pre_retirement income based around key income range (2020-21) 
![image](https://github.com/braydonnugent/Project1_Group4/assets/142812919/c5cb94c7-0208-47ea-ac67-39560b52c0bb)

Code Screen Shot displaying evidence to draw difference between Bar Charts
![image](https://github.com/braydonnugent/Project1_Group4/assets/142812919/5bebc85e-8d40-482e-9fbd-53ae2a7f08a9)

Code Results Screen Shot
![image](https://github.com/braydonnugent/Project1_Group4/assets/142812919/7d240d8e-1a6e-4ad9-bf0f-cb5cbe8f8281)

Note: You will find charts in both images representing 'Partners weekly income from all sources per week'. It was later found to be not relevant enough to implement in our presentation.

Dictionaries:
new_column_names: replaces headers in order to reduce length of titles in charts. (Specifier of data being in thousands is represented in the y axis of the charts).
income_categories: holds necessary income categories & reference values for sorting
income_classification: holds necessary income categories & reference values for sorting

##Breakdown of 'Characteristics of Retirees.xlsx' file

raw_data: derived from initial file, contains all relevant rows in regards to the question straight from 'Characteristics of Retirees.xlsx' file.
 
tidied_retirement_df: derived from raw_data, eliminating rows titled 'TOTAL' in order to not compromise data.

generalised_df: derived from tidied_retirement_df, only keeping rows where the 'Sex' column had the input 'Persons' (recognising this data is the total genders data).

income_df: derived from generalised_data, only keeping relevant classifications & categories (held by income_categories & income_classification).
Columns include 'Year', 'Classification', 'Category', (The 5 Age brackets), 'Total Retirees (thousands) & a Reference column (to order future df's when grouping).

chart_data: derived from income_df, equipped with relevant columns to visualise the summary of retirees incomes before retirement based on their age range via bar chart
        
chart_data2: deriving from income_df, equipped with relevant columns to visualise summary of grouped income via pie graph
---------------------------

CONTENT WITHIN 'Retirement Analysis - GD'
--------------------------------------------
Adding to question what factors influence early retirement, 3 categories of interest were identified and analysed from the population in the dataset ‘ Characteristics of Retirees - clean’. The dataset is filtered for the category of interest and the resulting data for each category is put into individual data frames and then analysed. 

A statistical analysis is performed taking into consideration total number of retirees for each of the subsets in the 3 categories. This is stored in the dictionary ‘statistics by population’.

Categories of Interest, Analysis and Findings
1)	Contribution to a Super Fund 
.	People who had contributed to a superannuation scheme
.	People who had not contributed to a superannuation scheme
Data frame created and used ‘super_contribution_df’. The charts created using this data frame are –
a)	To show retirees by age group for the 'super contribution' category
b)	To show average age at retirement by category

![image](https://github.com/braydonnugent/Project1_Group4/assets/144679119/87dc16c6-891c-4481-aab0-a059aa8da3c4)
![image](https://github.com/braydonnugent/Project1_Group4/assets/144679119/7ea24f07-0e3a-4fd6-a1fa-e00277c9345c)


2)	Health Condition
.	People with a long-term health condition
.	People without a long-term health condition
Data frame created and used ‘health_condition_df’. The charts created using this data frame are –
a)	To show retirees by age group for the 'health condition' category
b)	To show average retirement age by income category for different health conditions. 

![image](https://github.com/braydonnugent/Project1_Group4/assets/144679119/56272edc-5e5a-43dd-a077-845bee82a392)
![image](https://github.com/braydonnugent/Project1_Group4/assets/144679119/2ecc4f64-f66f-4941-a10f-67013f5ff21c)

3)	Reason for leaving last job
.	Retired, left last job to retire
.	Retired, lost last job due to illness or injury
.	Retired, lost last job for economic reasons (retrenched)
Data frame created and used ‘leave_job_df’. The charts created using this data frame are –
a)	To show retirees by age group for the category 'reason for leaving job'.
b)	To show average age retirement age by income category for various reasons for leaving the job.

![image](https://github.com/braydonnugent/Project1_Group4/assets/144679119/baa9bb93-d7d4-4e88-9e15-2eb0f9ebf830)
![image](https://github.com/braydonnugent/Project1_Group4/assets/144679119/a8e5fec2-455c-446d-b5f5-3399aeddf76b)

---------------------------------------------

Key Findings/Analysis:
---------------
  .pre_retirement income or super contribution is not indiciative of early retirement.
  .people with higher incomes appeared to retire later than those with a lower income.
  .financial struggle is significantly less of a factor than anticipated via the hypothesis.
   (to elaborate, there was no trendpoint to suggest superannuation contributions was a factor).
  .injury or illness has been proven to be the main factor resulting in younger retirement.
  

**Limitations**
---------------
  .There was no expression of the entire population sample total in the dataset as it came pre aggregated.
  .In addition, there was no data stating how much of the total sample did not fit a category, so it was hard to compare data.
  


