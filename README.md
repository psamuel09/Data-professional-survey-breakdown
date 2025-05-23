# Data-professional-survey-breakdown
This report cuts across the programmer's reaction towards their job, motivation level and their residence.

## Project overview

This Data Analytics project aims to provide insights into programmer's motivation and worklife balance in their various job role and country of residence. By analysing various aspects of the job role data,we seek to identify trends, and gain deeper understanding of most used programming language and how programmers are happy with their company's work life balance policy.

## Data Sources
Survey Questionaire

## Tools

- PowerBi and Power Query - Data cleaning, Data Analysis, Creating Reports 
 - [Download here (https://www.microsoft.com/en-us/power-platform/products/power-bi/downloads)


## Data Cleaning/Preparation 

In the initial data preparation phase, I performed the following task:
1. Data Loading and inspection.
![Image](https://github.com/user-attachments/assets/4dcb6aaf-6e07-407b-a655-66a20e6516f7)
![Image](https://github.com/user-attachments/assets/b9029187-3def-49ce-b36c-9cc27adf9f69)

From the image above, i had to click on transform so that i can inspect and remove un wanted data from the power query environment, before loading it to the powerBi environment.

3. Handling Missing Values by deleting unneeded columns and roles.

![Image](https://github.com/user-attachments/assets/0f5e2c62-e887-44f0-876b-cf82d6fcad79)

4. Data Cleaning and formatting by using appropriate data type and figures.

![Image](https://github.com/user-attachments/assets/5eee52ee-52d1-437f-b818-7c1739422e58)

Using the Split By Column to remove unwanted characters.
![Image](https://github.com/user-attachments/assets/2b30bd81-bb42-4a30-bc99-f96b91d338f8)

![Image](https://github.com/user-attachments/assets/b6ab3fd9-46d2-46b2-9d69-bae94d58aa7e)

The Image above is the Yearly range of Salary, from the two values given, i will create a new column called average yearly salary by firstly detaching every iphen and letter from the values to make calculation easier.


The image below is the result gotten after splitting the initial column, and deleting any other thing attached to the numbers like "K" and "K" column and iphen will be the next action to be taken.

![Image](https://github.com/user-attachments/assets/48ee49b0-4d4b-4b85-bb1a-ab7e28433c35)

![Image](https://github.com/user-attachments/assets/418c1190-3874-4a39-a1a5-ebb07f511e54)

![Image](https://github.com/user-attachments/assets/25ea65f6-980a-4f92-a6d8-afa54a65c1a9)

![Image](https://github.com/user-attachments/assets/25963420-3e99-4ba2-ba5d-681f283abad5)

After getting just the two values, its time to write formular to get the average value in a new column called Average Salary, see image below;

![Image](https://github.com/user-attachments/assets/938f44be-8b80-42b1-af4b-01edde79caf1)

![Image](https://github.com/user-attachments/assets/5e10c74d-7563-4080-9893-82bae5db887d)

## Exploratory Data Analysis

EDA involved exploring the Proffessional survey data to answer key questions, such as:

- How Many people took the Survey

![Image](https://github.com/user-attachments/assets/3576e91e-a655-4dfb-b929-a5581ce0982c)

 This is gotten from the total Count of unique_ID column.

- Average Age of survey taker

![Image](https://github.com/user-attachments/assets/f9f4ea1a-a147-4bbc-833b-63e52f00c2a8)

 This can either be gotten manually by adding up the ages of all the survey takers and divide the total by the count of the survey takers. or by simply clicking on the average button while selectig the age column.
  
- Average Salary in respect to Job Titles

![Image](https://github.com/user-attachments/assets/d6b7e0b4-7978-4360-9583-c85215db38aa)

The average salary in respect to job title from data science to database developer, according to the survey takers from the five countries USA, Canada, UK, India and others.

- The most used or favourite programming


![Image](https://github.com/user-attachments/assets/8069ed52-efce-4537-9744-df8f898196e4)

According to the four countries, python is the most used programming Language.
  
- How Happy are programmers with Work life Balance and Salary.

![Image](https://github.com/user-attachments/assets/2a0bc228-801d-4b47-b538-62f7cfa15a3a)

Programmers are slightly happy with work life Balance and Salary from the image result above.

- Average Salary by sex.

![Image](https://github.com/user-attachments/assets/9ca7fc11-57ee-45b9-bedc-fcbee8e4b4a6)

The average Salary of Male is slightly higher than that of the female.

## Data Analysis & Results/Findings


![Image](https://github.com/user-attachments/assets/7411a86d-9b13-4bef-8c8e-818685c52f45)



The Analysis results are summarized as follows:
From these major countries United States of America, United Kingdom, Canada and India, and other part of the nation, but most of the survey takers were from those four countries, it was observed that Python is the most used and also most peoples favourite programming language, the reason is its really the most easy to learn Language, and Java is the least used programming Language, Hence it's used by few people and there is no much competition in that category.  
On the other hand Data scientist are the most paid proffession, followed by Data Engineer, and the Least paid in data category is Database Developer.

## Recommendations

Based on the analysis, we recommend the following:
looking at the most used or favourite programming language and the less used programming language, python topping the chart and Java being the least used, this sends a signal that, python is an easy to learn and use programming language with a lot of users, and java is a complex programming language that has just few people writing it and learning it.

- For someone that might be frightened by high competition in the programming indusrty Java should be their best option.
- And for a prospective programmer that wants an easy to understand language, python should be their best option. 


## Limitations

I had to remove all zero values from .... they would have affected the accuracy of my conclusion from tyhe analysis,


## References
1. Alex the analyst
