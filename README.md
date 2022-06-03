# School District Analysis

## Project Overview
A School Board has requested that an analysis be done on the math and reading grades for students from Grades 9 - 12 in various schools within under the control of the board. The board would like to obtain information about the following:

1. Remove the 9th Graders Scores from Thomas High School (due to Academic Dishonesty) and provide an updated summary of school performances in the district.
2. Show the Top 5 and Bottom 5 Performing Schools by Overall Passing %.
3. Summarize the average math score for each grade from each school.
4. Summarize the average reading score for each grade from each school.
5. Show the average scores by school spending per student, by school size, and by school type.

## Resources
- Data Source: schools_complete.csv, students_complete.csv
- Software: Python (3.7.13), Visual Studio Code (1.67.2), Pandas (1.3.5), Jupyter Notebook

# Results
## Purpose
As a result of removing the reading and math grades of 9th Graders at Thomas High School, the summaries constructed earlier in the Module file are different to the summaries constructed in the Challenge file. The following results will outline the effect of removing those grades on the results.

## Changes in District Summary
In the District summary, as shown below, the Average Math and Reading Scores stayed the same almost. Additionally, the % of students that passed Math and reading fell slightly, by 0.1 percentage points each, leading to a decrease in the overall passing % by 0.3 percentage points. Therefore, there was not a significant affect of removing the Thomas High School 9th Graders scores on the District Summary.

Before:
![District Summary (Before)]()

After:
![District Summary (After)]()

## Changes in Schools Summary
In the School Summary, the only values that changed slightly were those from Thomas High School. The removal of the 9th Graders grades from Thomas High School had no effect on the scores of students from other schools. The changes in the Thomas High School numbers will be mentioned in the next section.

## Changes in Thomas High School Summary
In the School Summaries for Thomas High School Before and After the removal of the Grade 9 Scores, we can see that there were not too many differences here either. Overall the passing % only dropped by 0.3 percentage points.

Before:
![Thomas Summary (Before)]()

After:
![Thomas Summary (After)]()

## Affect on Rankings
As the effect of replacing the 9th grades scores of Thomas High School only had a very miniscule effect on its average scores, the overall standing of Thomas High School (by Overall Passing) has not been affected. As shown below, Thomas High School still maintains is 2nd Position in the ranking of the schools in the district.

Before:
![Top 5 (Before)]()

After:
![Top 5 (After)]()

## Other Metrics
### Math and Reading Scores by Grade
The only change in the Math and Reading Scores by Grade is that for 9th Graders in Thomas High School in both Math and Reading it shows NaN instead of a number. All other numbers are exactly the same before and after this removal.

### Scores by School Spending per Capita
The only difference in the Scores by School Spending per Capita is the % Passing Reading for the $631 - $645 subset is decrease of 0.05 percentage points which led to the overall passing % also decreasing by approximately 0.05 percentage points. This is only due to Thomas High School being a part of the $631 - $645 subset.

### Scores by School Size
The only difference in the Scores by School Size is the % Passing Reading for the Medium (1000 - 1999) subset is decrease of 0.05 percentage points which led to the overall passing % also decreasing by approximately 0.05 percentage points. This is only due to Thomas High School being a part of the Medium (1000 - 1999) subset.

### Scores by School Type
There was no change in the reading and math scores by School Type.


# Summary
The only changes that took place in the analysis after the reading and math scores were replaced for the 9th Graders of Thomas High School were:
- A decrease of 0.3 percentage points in the overall passing % in the district summary.
- A decrease of 0.3 percentage points in the overall passing % of the Thomas High School summary.
- A decrease of 0.05 percentage points in % Passing Reading and % Overall Passing for the $631 - $645 subset of the Scores by School Spending per Capita Summary.
- A decrease of 0.05 percentage points in % Passing Reading and % Overall Passing for the Medium (1000 - 1999) of the Scores by School Size Summary.