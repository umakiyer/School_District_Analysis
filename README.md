# School District Analysis

## Background
Analyzing the student data &amp; school district budget 
* The data file shows evidence of academic dishonesty in Math & reading scores of Thomas High schools 9th grade.
* The schoolboard want the school district analysis to be rerun after making null the 9th grade score for math & reading for Thomas High School.

## Deliverable 1: Replaceing  Ninth-Grade Reading and Math Scores with Null ( NaN) 
* The student data file before replacing the score

![School_data_original](Images/Student_Data_Original.PNG) 

Using the "loc' function replaced the math & reading  score of 9th grade students in Thomas High School. 

* The student data file after  replacing the score with Na
![School_data_original](Images/Student_Data_After_Replacing_with_NaN.PNG)

## Deliverable 2: The School District Analysis 
### 1. District Summary of the school 
*  Merged the student & school data nto one data frame using the function "merge'.
* Calculated the total budget of the school( sum of the the budget column)
* Calculated the average mat & reading scores of teh student
* Calculated the number of students in 9th grade in Thomas High School & the total number of students in school district. 
* Subtracted the number of student in 9th grade from Thomas High School to get the new total number of students.
* Calculated the passing math & reading score, average math & reading score, percentage of the math & reading score, overall passing percentage of the students( without the 9th grade Thomas High School student)
* Created dataframe for the district school summary.

District School Summary with 9th Grade Thomas High School Students
![District_School_Summary](Images/School_District_Summary_with_9th_gradeTHS.PNG)

District School Summary without 9th Grade Thomas High School Students
![District_School_Summary](Images/School_District_Summary_without_9th_gradeTHS.PNG)
   
### 2. The School Summary
* Calculated the per capita spending for each school
* Calculated the average math & reading score for each school( using the 'groupby' function)
* Calculated the passing math & reading score & Overall passing.
* Calculated the percenatge of the passing math & reading score & Overall passing.
* Created the dataframe using the above data.

The School Summary with 9th Grade student Thomas High School included

![School_Summary](Images/School_Summary_with_9th_gradeTHS.PNG)

The School Summary with 9th Grade student Thomas High School excluded

![School_Summary](Images/School_Summary_without_9th_gradeTHS.PNG)

### 3. The top 5 and bottom 5 performing schools, based on the overall passing rate
* Using the sort_values function on the overall passing score for the school created data frame for top 5 schools & bottom 5 schools in the district.

The top five performing school with 9th garde student from Thomas High School included.

![image](Images/Top_5_School_with_9th_grade_THS.PNG)

The top five performing school with 9th garde student from Thomas High School excluded.

![image](Images/Top_5_School_without_9th_grade_THS.PNG) 

The bottom five performing school with 9th garde student from Thomas High School included.

![image](Images/Bottom_5_School_with_9th_grade_THS.PNG)

The bottom five performing school with 9th garde student from Thomas High School excluded.

![image](Images/Bottom_5_School_without_9th_grade_THS.PNG)

### 4. The average math score for each grade level from each school
* Created a Series of scores by grade levels using conditionals.
* Created a Series by the school name for the average math score.
* Set the index name to none. 

Grade wise math score with 9th grade student from Thomas High School included.

![image](Images/Grade_wise_math_score_with_9th_grade.PNG)

Grade wise math score with 9th grade student from Thomas High School excluded.

![image](Images/Grade_wise_math_score_without_9th_grade.PNG)

### 5. The average reading score for each grade level from each school
* Created a Series of scores by grade levels using conditionals.
* Created a Series by the school name for the average reading score .
* Set the index name to none. 

Grade wise reading score with 9th grade student from Thomas High School included.

![image](Images/Grade_wise_reading_score_with_9th_grade.PNG)

Grade wise reading score with 9th grade student from Thomas High School excluded.

![image](Images/Grade_wise_reading_score_without_9th_grade.PNG)

### 6. The scores by school spending per student, by school size, and by school type 
* Using the 'Describe' function , found the minimum & maximum of the per school capita data frame.
* created  separate "spending bins' & group names for spending by students, school size & school type.
* created data frame for each catogory & formatted the colums.

 ### 6a. The score by School Spending 
 ![image](Images/Score_by_school_spending.PNG)   

   ### 6b.The score by School Size
![Image](Images/Score_by_school_size.PNG)

   ### 6c. The score by School Type
![image](Images/Score_by_school_district.PNG)
