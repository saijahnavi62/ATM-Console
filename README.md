ATM-Console
Backend service for ATM operations using core java. Handles user authentication, account transactions

This is a pure Java-based ATM application that simulates basic banking operations such as checking balance, withdrawing cash, and depositing money. The application connects to the database to store and retrieve customer details securely.

Features

->User authentication using PIN

->Balance inquiry

->Cash withdrawal and deposit

->Data persistence using MySQL database 

->Console-based user interface

->No transaction history is stored for simplicity.


Technologies Used

*Java (Core Java)

*JDBC for database connectivity(Manually connecting to the database using JDBC and closing the connection after use)

*MySQL 



Database

->Stores user account details like name, PIN, and account balance.

->Admin details, pin


Functional

It supports both customer-side features (like checking balance and withdrawing cash) and admin-side features (like managing customer accounts). The system uses a relational database to store basic customer details and account balances.


