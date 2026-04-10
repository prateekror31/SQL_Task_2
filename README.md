# 📊 SQL_Task -2

![SQL](https://img.shields.io/badge/SQL-Practice-blue)
![Level](https://img.shields.io/badge/Level-Beginner%20to%20Intermediate-green)
![Database](https://img.shields.io/badge/Database-MySQL-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📌 Project Overview

This repository contains a structured SQL practice exercise focused on **database design, table relationships, and query operations** using real-world employee and department data.

The project simulates an organizational database where employees are assigned to departments, enabling practice of SQL concepts from basics to intermediate level.

---

## 🗂️ Database Structure

### 🔹 Database Name
`exercise`

### 🔹 Tables

#### 1. Departments
- `Code` (Primary Key)
- `Name`
- `Budget`

#### 2. Employees
- `SSN` (Primary Key)
- `Name`
- `LastName`
- `Department` (Foreign Key → Departments.Code)

---

## 🚀 Features & Concepts Covered

### ✅ Database & Table Creation
- Creating databases and tables
- Defining **Primary Keys** and **Foreign Keys**

### ✅ Data Insertion
- Inserting multiple records into tables

### ✅ Filtering & Conditions
- `WHERE`, `LIKE`, `IN`, `NOT IN`

### ✅ String Functions
- `CONCAT()` for combining first and last names

### ✅ Aggregations
- `COUNT()` with `GROUP BY`

### ✅ Data Manipulation (DML)
- `UPDATE` (budget changes, reassignment)
- `DELETE` (removing records)

### ✅ Schema Modifications (DDL)
- `ALTER TABLE`
  - Rename columns
  - Add new columns (e.g., `city`)

---

## 📈 Key SQL Operations Performed

- Retrieve employees based on name patterns  
- Filter employees by department  
- Count employees in each department  
- Add new department and employee records  
- Reduce department budgets by 10%  
- Reassign employees between departments  
- Delete employees from specific departments  
- Modify table structure dynamically  

---

## 📁 Files in Repository

| File Name | Description |
|----------|------------|
| `sql_Ex2_Questions.sql` | Contains problem statements and schema |
| `sql_Ex2_solutions.sql` | Contains all SQL queries and solutions |

---

## 🛠️ Tools Used

- MySQL / SQL
- DBMS concepts
- Query Editor (MySQL Workbench / VS Code / DBeaver)

---

## 🎯 Learning Outcome

After completing this project, you will understand:

- How relational databases work  
- How to write efficient SQL queries  
- How to manage and modify database schemas  
- How to perform real-world data operations  

---

## 📌 How to Run

1. Open MySQL Workbench (or any SQL editor)
2. Run `sql_Ex2_Questions.sql` to create tables and insert data
3. Run `sql_Ex2_solutions.sql` to execute queries
4. Analyze outputs

---

## 🤝 Contributing

Feel free to fork this repository and practice more SQL queries or improve existing ones.

---

## 📧 Contact

**Prateek Kumar**  

---

⭐ If you found this helpful, don't forget to star the repo!
