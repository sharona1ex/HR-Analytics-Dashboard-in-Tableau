# HR-Analytics-Dashboard-in-Tableau
Objective: Analysis of attrition rate in a company and exploring various factors like department, age, gender and employee engagement.

**Why is analysing attrition important?** <br>
Employee attrition is a vital aspect to any company. If a company has high attrition rate, then its hiring costs will increase, productivity of teams and moral of existing employees may decrease resulting in more attrition. Therefore, HR department has to keep a tab on attrition to protect a company from potential downfall.

(If you are eager to see my tableau report, click [this](https://public.tableau.com/views/HRanalytics_17061454213120/FinalDash?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link))

![image](https://github.com/StarRider/HR-Analytics-Dashboard-in-Tableau/assets/30108439/82a10bbf-1005-44b4-a348-bbec6bf4cad2)


Let's follow the 5 step process of data analysis,

1. Identifying HR related questions about attrition.
2. Collecting and storing data
3. Cleaning and preparing data
4. Analyzing data
5. Visualizing and Communicating

## 1. Identifying HR related questions about attrition.

### Overview companies workforce
1.1 How many employees were there?<br>
1.2 How many left? How many are currently working?<br>
1.3 What is the attrition rate?<br>

### Department wise details
1.4 How many employees are working in specific department? How many left?<br>
1.5 What is the attrition rate w.r.t a department?<br>
1.6 Which department has the highest attrition rate?<br>

### Employee Overview
1.7 Which age group is leaving the company and which age group is more stable?<br>
1.8 Are Female employees more likely to stay that Male employees?<br>
1.9 What is the attrition rate with certain type employees with a specific education field?<br>

### Employee Engagement Scores
1.10 How many people are satisfied with their jobs?<br>
1.11 How many are involved in their jobs?<br>
1.12 Same questions on environment satisfaction, work life balance.<br>
1.13 How do each type of employees w.r.t above 3 question correlate with attrition. (Do those quit the most who rated poor in all facets of employee engagement metrics?)<br>

## 2. Collect and store data.
I downloaded the data from [here](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset).

## 3. Clean and prepare data.
The dataset had no null values and the values were also consistent. (Checkout [my other repo](https://github.com/StarRider/Data-Science-Job-Market-Tableau-Dashboard#3-clean-and-prepare-data) to know, how I got this null % for each column)
```
Columns                       Null %
------------------------------------
Attrition                     0.0
Business Travel               0.0
CF_age band                   0.0
CF_attrition label            0.0
Department                    0.0
Education Field               0.0
emp no                        0.0
Employee Number               0.0
Gender                        0.0
Job Role                      0.0
Marital Status                0.0
Over Time                     0.0
Over18                        0.0
Training Times Last Year      0.0
Age                           0.0
.
.
.
Years In Current Role         0.0
Years Since Last Promotion    0.0
Years With Curr Manager       0.0
```

## 4. Analyse data.
During my analysis I observed the following for this dataset,

1. This business is a small size business with employees less 1500.
2. It has a high attrition rate of ~ 16% because it's more than the global average of [12-15%](https://engagedly.com/blog/employee-turnover-rate-by-industry/#:~:text=As%20of%20the%20latest%20available,lower%20depending%20on%20various%20factors.)
3. Despite R&D departement having the highest number of employees leaving the firm, Sales department has the highest department wise attrition rate followed by HR department.
4. Young employees in their 20s and 30s are showing a higher tendencies to quit.
5. As expected those employees who rated poor in the employee engagement metrics quit the most compared to others.

## 5. Visualize and communicate the data
I have visualized this data in tableau. Follow this link [here](https://public.tableau.com/views/HRanalytics_17061454213120/FinalDash?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)


