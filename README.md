# BankingConsoleApp_CPP

## Overview

The Simple Banking System is a console-based application that demonstrates fundamental Object-Oriented Programming (OOP) principles. It allows users to manage multiple bank accounts, providing functionalities such as deposits, withdrawals, and balance inquiries. This project serves as a learning tool for B.S. Computer Science students and anyone interested in understanding basic banking operations through programming.

## Features

- **Object-Oriented Design**: Utilizes OOP principles for better code organization and modularity.
- **Multiple Account Management**: Supports the storage and management of multiple bank accounts.
- **Core Functionalities**:
  - Deposit funds into an account
  - Withdraw funds from an account
  - Check account balance
- **Basic Error Handling**: Implements simple error handling to manage invalid operations.

## Program Breakdown

### Classes and Methods

- **Class `BankAccount`**: 
  - Attributes:
    - `owner`: The name of the account holder
    - `accountNumber`: Unique identifier for each account
    - `balance`: Current balance of the account
  - Methods:
    - `deposit(amount)`: Adds funds to the account
    - `withdraw(amount)`: Removes funds from the account
    - `displayAccountDetails()`: Shows account owner, number, and balance

- **Vector to Store Accounts**: 
  - Utilizes a vector to store multiple `BankAccount` objects for efficient management.

- **User Menu**:
  - Provides options to create an account, deposit funds, withdraw funds, check balance, or exit the application.

- **Helper Function `findAccount(accountNumber)`**:
  - Searches for an account using the provided account number and returns the corresponding `BankAccount` object.

## Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/worldsocoled/BankingConsoleApp_CPP.git
   cd BankingConsoleApp_CPP

## Contributing

Contributions are welcome! If you have suggestions for improvements, additional features, or bug fixes, please follow these steps:

1. **Fork the repository.**
2. **Create a new branch for your feature or bug fix:**
   ```bash
   git checkout -b feature/your-feature-name
3. **Make your changes and commit them.**
   ```bash
   git commit -m "Add your message here"
4. **Push to your branch.**
   ```bash
   git push origin feature/your-feature-name
5. **Open a pull request with a clear description of your changes.**

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Tags
- C++
- Console Application
- Object-Oriented Programming
- Open-source
