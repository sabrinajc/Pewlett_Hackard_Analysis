# Pewlett_Hackard_Analysis

## Overview
This project focuses on determining the number of employees that are reaching the stage of retirement. We will be using pgAdmin, SQL to perform the total retiring employees by title. Moreover, this project will identify those who are eligible to participate in a mentorship programs.

## Results
- The retirement titles table presents all the retiring employees whose birthday falls between 1952 and 1955. Table 1 also shows the title, from date and to date of each employee. As shown, there are duplicate entries in the table because we haven’t filtered the table for the most current position.
![retirement.png](Data/retirement.png)
<br> Table 1: retirement titles

- The unique titles table uses DISTINCT ON statement to retrieve the first occurrence employee number, and it sorts the table in ascending order by the employee number and depending order by the to_date. As table 2 shown, there is no duplicate entry for some employees, and the title has been updated to the most current position.
![unique_titles.png](Data/unique_titles.png)
<br> Table 2: unique titles

- The retiring titles table shows the total retirement employees by their title. Senior Engineer has the most retiring employees, and only 2 manager are retiring.
![retiring_titles.png](Data/retiring_titles.png)
<br> Table 3: retiring titles

- The mentorship eligibility table determines the employees who were born between 01/01/1965 and 12/31/1965, who are eligible to participate in a mentorship programs.
![mentorship.png](Data/mentorship.png)
<br> Table 4: mentorship eligibility

## Summary





Results: Provide a bulleted list with four major points from the two analysis deliverables. Use images as support where needed.
Summary: Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."
How many roles will need to be filled as the "silver tsunami" begins to make an impact?
Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

<br> Please see Figure 1 for details:
![PyBer_summary_DataFrame.png](Analysis/PyBer_summary_DataFrame.png)
<br> Figure 1: PyBer_summary_DataFrame