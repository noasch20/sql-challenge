# Employee Database: SQL Schema & Queries  

## Project Overview  
This project creates and manages an employee database using **PostgreSQL**. It defines relational tables for employee records, department assignments, salaries, and job titles. The database is structured using **primary keys, foreign keys, and constraints** to ensure data integrity.  

Additionally, a set of **SQL queries** is provided to retrieve employee details, department assignments, salary information, and more.  

---

## Database Schema  

The database consists of six tables:  

1. **departments** – Stores department names and IDs.  
2. **employees** – Stores employee details such as name, birth date, hire date, and title.  
3. **titles** – Defines job titles assigned to employees.  
4. **dept_emp** – Links employees to their respective departments.  
5. **dept_manager** – Tracks department managers.  
6. **salaries** – Stores salary records for employees.  

## Schema Definition / ERD
![sql-challenge-erd](https://github.com/user-attachments/assets/a7f807fd-9848-4808-b643-2d3fa5591fa6)

## Queries
The project includes queries to analyze and extract key insights from the employee database.  

1. **Retrieve Employee Salary Information**  
   - Displays each employee’s number, name, gender, and salary.  

2. **Find Employees Hired in 1986**  
   - Lists employees who were hired in the year 1986, along with their hire date.  

3. **List Department Managers**  
   - Shows department managers along with their department number, department name, employee ID, and full name.  

4. **Find Each Employee’s Department Assignment**  
   - Displays department number, employee number, full name, and department name.  

5. **Identify Employees Named 'Hercules B'**  
   - Retrieves employees whose first name is "Hercules" and whose last name starts with "B".  

6. **List All Employees in the Sales Department**  
   - Displays employee details for those working in the "Sales" department.  

7. **Find Employees in Sales and Development**  
   - Lists employees working in both the "Sales" and "Development" departments, along with their department name.  

8. **Analyze Most Common Last Names**  
   - Counts how many employees share the same last name and sorts them in descending order of frequency.
