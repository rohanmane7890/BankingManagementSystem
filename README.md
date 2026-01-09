## 🏦 Banking Management System (Java + MySQL)
# 📌 Project Description

The Banking Management System is a console-based Java application that allows users to register, open bank accounts, and perform banking operations such as credit, debit, money transfer, and balance inquiry.
The project uses JDBC to connect Java with a MySQL database and ensures secure transactions using SQL and transaction management.

# ✨ Features
- User Registration & Login
- Open New Bank Account
- Secure Credit & Debit Transactions
- Money Transfer Between Accounts
- Balance Inquiry
- Transaction Handling using JDBC (commit & rollback)
- Data stored and managed using MySQL

# 🛠️ Technologies Used
- Java (Core Java)
- JDBC (Java Database Connectivity)
- MySQL Database
- SQL
- IntelliJ / Eclipse

# ⚙️ Core Functionalities Explained
# 🔐 User Authentication
Users must register and login before performing banking operations.
Email & password validation using SQL queries.

# 💳 Account Management
New account creation with unique account number generation.
One account per registered email.

# 💰 Transactions
- Credit Money: Adds balance after PIN verification.
- Debit Money: Deducts balance with insufficient balance check.
- Money Transfer:
- Uses JDBC transactions
- Ensures atomic operations using commit() & rollback()

# Transaction Handling Example
connection.setAutoCommit(false);
connection.commit();
connection.rollback();

Ensures data consistency during money transfers.

# 🔒 Security Features
- PIN-based transaction validation
- User authentication via email & password
- Database-level transaction safety

# Future Enhancements
- Encrypt passwords and security pins
- Add transaction history
- Implement admin panel
- GUI using JavaFX or Swing
- Convert to Spring Boot REST API

  GitHub:https://github.com/rohanmane7890/BankingManagementSystem
