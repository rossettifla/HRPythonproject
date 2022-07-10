# HRPythonproject
Data set: I am utilizing a Human Resources data set from Kaggle (https://www.kaggle.com/datasets/rhuebner/human-resources-data-set). This data set includes a list of fictitious employees and additional information such as names, DOBs, age, gender, marital status, date of hire, reasons for termination, department, position title, pay rate, manager name, and performance score.

Project Scope: My goal with this project is to verify the gender differences from this data set and answer questions such as:
•	How many females and males does this company have?
•	What is the salary average for males and females?
•	What is the average tenure for females or males?
•	What is the average age for females or Males?  
•	Are we hiring more women each year? 
•	What is the voluntary and involuntary termination for females or males leaving the company? 

Feature 1: Read in data from a local csv file, excel file, by using Pandas read_ functions. 
•	Read the data from the CSV File. 

Feature 2: Use custom functions or lambdas to perform specific operations to clean or manipulate your data, return those values, then use them in other parts of your project.
•	Verify if the employee is active or terminated – already in the data set. >> This is what I originally submited in th project plan. I noticed that the data set already has employee status. So I decided to change this to calculate the age of each employee based on date of birth, and drom date of hire, extract the year of hire.  
Feature 3: Do 5 basic calculations with Pandas, like finding the sum(), median(), mean(), or mode() of a column. You could divide two columns by each other. You could multiple a column by a random integer. You could use string operations and find the most common letter in a given entry.
•	Count the number of Females and Males, calculate the salary average, calculate the average of tenure per gender, and count voluntary and involuntary termination for females and male.

Feature 4: Make 2 basic plots with matplotlib, seaborn, or any other kind of visualization library that you think looks interesting.

