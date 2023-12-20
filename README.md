HR-Dashboard-MySQL-PowerBI
![image](https://github.com/thisisrahulll/HR-analytics/assets/105283611/77a85613-9b05-441c-b539-2ab938e0aac5)
The dataset was cleaned and queried using SQL inside MySQL Workbench Notebook and visualized using PowerBI

Data Used Data: HR Data with over 22000 rows from the year 2000 to 2020. (Complete import was not done.)

Data Cleaning and Analysis: MySQL, MySQL Workbench

Data Visualization: PowerBI

Questions 
What is the gender breakdown of employees in the company? 
What is the race and ethnicity breakdown of employees in the company? 
What is the age distribution of employees in the company? 
How many employees work at headquarters versus remote locations? What is the average length of employment for employees who have been terminated? 
How does the gender distribution vary across departments and job titles? 
What is the distribution of job titles across the company? 
Which department has the highest turnover rate? What is the distribution of employees across locations by state? 
How has the company's employee count changed over time based on hire and term dates? 
What is the tenure distribution for each department? 

Summary of Findings 
There are more male employees The white race is the most dominant while Native Hawaiian and American Indian are the least dominant. The youngest employee is 20 years old and the oldest is 57 years old 5 age groups were created (18-24, 25-34, 35-44, 45-54, 55-64). A large number of employees were between 25-34 followed by 35-44 while the smallest group was 55-64. A large number of employees work at the headquarters versus remotely. The average length of employment for terminated employees is around 7 years. 7, The gender distribution across departments is fairly balanced but there are generally more male than female employees. The Marketing department has the highest turnover rate followed by Training. The least turnover rate are in the Research and Development, Support, and Legal departments. A large number of employees come from the state of Ohio. The net change in employees has increased over the years. The average tenure for each department is about 8 years with Legal and Auditing having the highest and Services, Sales, and Marketing having the lowest. Limitations Some records had negative ages and these were excluded during querying(967 records). The ages used were 18 years and above. Some term dates were far into the future and were not included in the analysis(1599 records). The only term dates used were those less than or equal to the current date.
