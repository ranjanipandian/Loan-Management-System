# 🏦 Loan Management System

A Java-based console application that manages loan operations for customers including Car Loans and Home Loans. Built using Core Java, JDBC, and MySQL.

## 📌 Features
- Apply for Car Loan and Home Loan
- View all loans by customer
- Calculate EMI for loans
- Exception handling for invalid loan scenarios
- Database connectivity using JDBC

## 🛠️ Tech Stack
- Java (Core Java, OOP)
- JDBC
- MySQL
- SQL Schema

## 📁 Project Structure

├── dao/
│   ├── ILoanRepository.java
│   └── LoanRepositoryImpl.java
├── entity/
│   ├── Loan.java
│   ├── CarLoan.java
│   ├── HomeLoan.java
│   └── Customer.java
├── exception/
│   └── InvalidLoanException.java
├── main/
│   └── MainModule.java
├── util/
│   ├── DBConnUtil.java
│   └── DBPropertyUtil.java
├── schema.sql
└── db.properties

## ⚙️ Setup Instructions
1. Clone the repository
2. Import into Eclipse or IntelliJ as a Java project
3. Run `schema.sql` in MySQL to create the database
4. Update `db.properties` with your MySQL credentials
5. Run `MainModule.java`
