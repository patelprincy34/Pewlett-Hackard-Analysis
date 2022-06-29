# Pewlett-Hackard-Analysis

### Overview
The purpose of this project was to determine number of employees retiring from Pewlett Hackard and identify them by their name and title and also determine which employees are eligible to participate in a mentorship program.

### Results 
* There are 72,458 retiring employees.
* Out of those employees leaving, there are 25,916 Senior Engineers, 24,926 Senior Staff, 9,285 Engineers,     7,636 Staff, 3,603 Technique Leaders, 1,090 Assistant Engineers, and 2 Managers.
* By combining the employees, department employees, and titles tables, the mentorship eligibility table was   created. The workers had to be born in 1965 and presently employed at PH in order to be   eligible for the   retiring/mentorship package.
* There were 1,549 employees eligible for mentorship program.

### Summary
* 72,458 roles will need to be filled as the "silver tsunami" begins to make an impact as these are the     number of employees that would be ready for retirement.
* Query: select * from retiring_titles;
* Based on the numbers there are only 1549 retirement-ready employees in the departments to mentor the     next generation of Pewlett Hackard employees. 
* Query: select * from mentorship_eligibilty;

### Resources
* Orginal datasets:

  * departments.csv
  * dept_emp.csv
  * dept_manager.csv
  * employees.csv
  * salaries.csv
  * titles.csv
* Software:
  * SQL
  * PostgreSQL
  * pgAdmin
* Employee_Challenge_starter_code.sql
