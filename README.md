Employee Management System:

Project Overview:
Employee Management System is a web-based application built using ASP.NET Core MVC (.NET 10) and SQL Server. 
It demonstrates CRUD operations, search functionality, dashboard metrics, and Entity Framework Core integration.
Technologies Used:
•	ASP.NET Core MVC (.NET 10)
•	C#
•	Entity Framework Core
•	SQL Server Express
•	Razor Views
•	Bootstrap 5
•	Git & GitHub

Features
•	Dashboard with Total Employee Count
•	View Employees
•	Add Employee
•	Edit Employee
•	Delete Employee
•	Search Employee by Name
•	Clear Search Results


EmployeeManagementSystem
│
├── Controllers
│   ├── HomeController.cs
│   └── EmployeeController.cs
│
├── Models
│   ├── Employee.cs
│   └── ErrorViewModel.cs
│
├── Data
│   └── ApplicationDbContext.cs
│
├── Views
│   ├── Home
│   ├── Employee
│   └── Shared
│
├── wwwroot
│
├── Program.cs
├── appsettings.json
└── EmployeeManagementSystem.csproj


Screenshots
Dashboard
Employee Management Dashboard

Total Employees: 7

[ View Employees ]
Employee List
-----------------------------------------------------
| Id | Name   | Department     | Salary | Actions   |
-----------------------------------------------------
| 1  | Shoaib | IT Development | 50000  | Edit/Delete |
| 2  | Shahid | HR             | 45000  | Edit/Delete |
-----------------------------------------------------

Search Employee
[ Search Employee Name ]

Result:
Shoaib
Add Employee
Name
Department
Salary

[ Save ]
Edit Employee
Update Employee Information

[ Update ]
Delete Employee
Are you sure you want to delete this employee?

[ Delete ]
Database Schema
Employees Table
Column	Data Type
Id	int
Name	nvarchar
Department	nvarchar
Salary	decimal


Install:
Visual Studio 2026
.NET 10 SDK
SQL Server Express
SQL Server Management Studio (SSMS)

Learning Outcomes

Through this project, the following concepts were implemented and understood:
MVC Architecture
Controllers
Models
Views
Entity Framework Core
Dependency Injection
DbContext
DbSet
LINQ
CRUD Operations
SQL Server Connectivity
Git & GitHub
Future Enhancements
REST API Integration
Swagger Documentation
Authentication & Authorization
Pagination
Sorting
Employee Details Page
Department Master Module
Role-Based Access Control

Author: Shoaib Janvekar

Learning ASP.NET Core MVC, SQL Server, Entity Framework Core, and Web API Development.
