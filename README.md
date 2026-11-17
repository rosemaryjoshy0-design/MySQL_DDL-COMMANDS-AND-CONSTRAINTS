# MySQL_DDL-COMMANDS-AND-CONSTRAINTS

## Overview
A foundational MySQL project demonstrating **Data Definition Language (DDL)** operations and **relational database constraints** through an `employee` database schema.

## Schema
* **`Departments`**: `department_id` (PK), `department_name` (NOT NULL, UNIQUE)
* **`Location`**: `location_id` (PK, AUTO_INCREMENT), `location` (NOT NULL, UNIQUE)
* **`Employees`**: `employee_id` (PK), `employee_name` (NOT NULL), `gender` (`ENUM('M', 'F')`), `age` (`CHECK >= 18`), `hire_date` (`DEFAULT CURRENT_DATE`), `designation`, `department_id` (FK), `location_id` (FK), `salary`

## Key Operations Covered
* **DDL**: `CREATE`, `ALTER` (add, modify, drop, rename columns), `RENAME`, `TRUNCATE`, and `DROP`
* **Constraints**: `PRIMARY KEY`, `FOREIGN KEY`, `UNIQUE`, `NOT NULL`, `CHECK`, `AUTO_INCREMENT`, and `DEFAULT`

## Tools Used
* MySQL 8.0+ / MySQL Workbench
