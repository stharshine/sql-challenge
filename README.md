# sql-challenge 
EmployeeSQL

# Data-Modelling:

EDR schema of the data tables can be represented via the below image
![Employees_EDR ](https://user-images.githubusercontent.com/105055655/213547569-34be7ced-0050-4509-bc8a-713971c98862.png)

However, it is very similar to the image below.
![Employees_EDR_example2](https://user-images.githubusercontent.com/105055655/213547638-c656de73-e1dd-484b-a763-2e5df62f8422.png)


Both images show that the connection between the tables can be represented differently but still show the same relationship to each other.

#Data Engineering
Looking at schena.sql, it is possible to see that the information imported from the 6 cvs files was used to create an SQL table for each (with specification to  types, primary keys, foreign keys, and other information).


#Data Analysis

Looking at table.sql, it is possible to observe the analysis of the data extrapolated:

  List the employee number, last name, first name, sex, and salary of each employee.
  List the first name, last name, and hire date for the employees who were hired in 1986.
  List the manager of each department along with their department number, department name, employee number, last name, and first name.
  List the department number for each employee along with that employee’s employee number, last name, first name, and department name. 
  List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.
  List each employee in the Sales department, including their employee number, last name, and first name.
  List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
  List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

