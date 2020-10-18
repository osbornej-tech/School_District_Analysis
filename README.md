# School District Analysis


## Overview of the school district analysis: 
This analysis provides a high-level snapshot of the district's key metrics, which includes performance based on budget, school size, type of school, average math and reading score.

## Results: 
Byomitting the math and reading scores for ninth grades at Thomas High School, the following changes are noted.

*How is the district summary affected?
There is a decrease in the average math score, % passing math and reading percentages, and % overall passing percentages. The average reading score, total number of students and the total budget remains the same. The overall passing percentage and average math scores decrease by a tenth; while, percent passing math decreased by 2-tenths.

<img src ='https://github.com/osbornej-tech/School_District_Analysis/blob/main/Resources/district_summary.png'>

*How is the school summary affected?
Significant decrease in the percent passing math, reading and overall passing percentage reported when ninth grade data is removed from the dataset. 

<img src ='https://github.com/osbornej-tech/School_District_Analysis/blob/main/Resources/School_summary.png'>

*How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
It caused a change in the rank for Thomas High School overall rating. As they were previously in the top 5 performing schools, they are neither in the top 5 or bottom 5 performing schools. 

*How does replacing the ninth-grade scores affect the following:
*Math and reading scores by grade
Math score was reported as NaN; all other average math scores per grades remained unchanged.

<img src ='https://github.com/osbornej-tech/School_District_Analysis/blob/main/Resources/average_math_score.png'>


Reading score 
Reading score was reported as NaN; all other average reading scores per grades remained unchanged.

<img src ='https://github.com/osbornej-tech/School_District_Analysis/blob/main/Resources/average_reading_score.png'>

*Scores by school spending
The total number of students, school budget, per student budget and the spending ranges per student remain unchanged. Omitting ninth grade data resulted in a decrease of the percents reported for passing math, passing reading, and overall passing.Because Thomas High School was in the $630-644 spending range per student, there is a significant decrease in the percentage of students passing math, reading and overall passing score as illustrated in the image below.

<img src ='https://github.com/osbornej-tech/School_District_Analysis/blob/main/Resources/school_spending.png'>

*Scores by school size
Omission of Thomas High School affected the medium school size data. Decrease is noted in all data points for medium sized schools.

<img src ='https://github.com/osbornej-tech/School_District_Analysis/blob/main/Resources/scores_shool_size.png'>

*Scores by school type
In general, the omission of Thomas High School ninth grade data did not affect the results.

<img src ='https://github.com/osbornej-tech/School_District_Analysis/blob/main/Resources/summary_school_type.png'>

## Summary:
 
 - Omitting ninth grade data affected the results reported when we view the data specifically related to the school. 
 - When included as part of a larger group, the omitted data had little to no effect on the results reported.
 - The omission data affected reports where math and reading scores were used to calculate a specific field. 
 - Furthermore, when ninth grade information was requested separately the NaN was reflected in the results. 
 - Omitting ninth grade scores, resulted in a change in the ranking for Thomas High School.

## Resources
Datasources: student_complete.csv, school_complete.csv
Software: Juptyer Notebook
Library: pandas
