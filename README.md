# employee_exit_surveys
Analyze employee exit surveys and reasons for leaving from exit surveys from employees of the Department of Education, Training and Employment (DETE) and the Technical and Further Education (TAFE) institute in Queensland, Australia.  This first part of this is a guided project with a set of questions to answer.  The last part is exploring the data further.  The goal of this project was to work on data cleaning, visualizations, and feature engineering.

First we answered the following quesitons:
* Are employees who only worked for the institutes for a short period of time resigning due to some kind of dissatisfaction? What about employees who have been there longer?
* Are younger employees resigning due to some kind of dissatisfaction? What about older employees?

Employees who were with the company longer were more likely to resign due to dissatisfaction than employees who were in the company for shorter periods. Out of the employess who resigned, 56% of established employees resigned due to dissatisfaction and 30% of the new employees resigned due to dissatisfaction. 

There is a 13% larger percentage of 55 and older leaving due to dissatisfaction than the 24 and younger group. 

The resignation due to dissatisfaction is more evenly distributed in the TAFE data between both the service and age categories.  

The DETE data had much larger ranges in dissatisfaction than TAFE. 

The percentage of males that resigned due to dissatisfaction was less than 3% more than females who resigned do to dissatisfaction. Gender does not appear to play a role in an employee resigning due to dissatisfaction.

The data sets both contain a lot of NaN values for reasons for leaving. We could drop them but it could potentially skew the data and produce unrepresentative results. For example, only half of the rows in the Tafe dataset have non null values for Interpersonal Conflict. Maybe it was left blank because they did not want to report true or maybe it was not applicable. We could potentially look at reasons for leaving based on job classification but these too have many missing values. We may not be able to see the full picture.  This was not the best dataset in terms of trying to get an comprehensive idea on reasing for employees leaving.  The dataset is small and full of NaN.  