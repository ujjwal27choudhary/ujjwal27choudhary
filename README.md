### Department Management System

This project implements a Department Management System with four different departments as classes:

1. **Super Department**
   - `departmentName`: Returns "Super Department"
   - `getTodaysWork`: Returns "No Work as of now"
   - `getWorkDeadline`: Returns "Nil"
   - `isTodayAHoliday`: Returns "Today is not a holiday"

2. **Admin Department**
   - `departmentName`: Returns "Admin Department"
   - `getTodaysWork`: Returns "Complete your documents Submission"
   - `getWorkDeadline`: Returns "Complete by EOD"

3. **Hr Department**
   - `departmentName`: Returns "Hr Department"
   - `getTodaysWork`: Returns "Fill today’s timesheet and mark your attendance"
   - `getWorkDeadline`: Returns "Complete by EOD"
   - `doActivity`: Returns "team Lunch"

4. **Tech Department**
   - `departmentName`: Returns "Tech Department"
   - `getTodaysWork`: Returns "Complete coding of module 1"
   - `getWorkDeadline`: Returns "Complete by EOD"
   - `getTechStackInformation`: Returns "core Java"

## Usage

The main driver class creates objects of HrDepartment, TechDepartment, and AdminDepartment, displaying their functionalities and whether today is a holiday.

## Expected Output

Welcome to Admin Department
Complete your documents submission
Complete by EOD
Today is not a Holiday

Welcome to HR Department
team Lunch
Fill today’s timesheet and mark your attendance
Complete by EOD
Today is not a Holiday

Welcome to Tech Department
Complete coding of Module 1
Complete by EOD
Core Java
Today is not a Holiday




