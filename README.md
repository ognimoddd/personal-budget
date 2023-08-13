# personal-budget

## Table of Contents: 
<li><b> Introduction </b></li>
<li><b>Technologies Used</b></li>
<li><b> Installation guide </b> </li>
<li><b>Images</b></li>

## Introduction

PersonalBudget is a tool that helps users manage their money. It allows users to create and manage their bank account, add/remove currency, view transaction history, set up budgets, manage debt, generate charts to visualize spending habits, and convert currencies. 

## Technologies Used
<li>Spring Boot with Spring Security, Hibernate, REST</li>
<li>Bootstrap, Thymeleaf</li>
<li>JavaScript, jQuery</li>
<li>JUnit5</li>
<li>MariaDB</li>

## Installation Guide

1. Download the project and import it to your IDE
2. Install XAMPP or WAMP then run the servers
3. Run the SQL script from the <b>personal_budget.sql</b> file
4. Create a user on the MySQL server and grant all privileges to the <b>personal_budget</b> database, ex:

```
CREATE USER 'admin'@'localhost' IDENTIFIED BY 'admin';
GRANT ALL PRIVILEGES ON `personal_budget`.* TO 'admin'@'localhost';
```
5. Edit the <b>application.properties</b> file located in the src\main\resources directory
   
<li>If you are running a port other than 3306, modify it on line 4 </li>
<li>Modify lines 5 and 6 to the correct username and password that you created</li>
<br>

6. Run the application by selecting DemoApplication.java as the main class

## Images

![60954598-8dbf5e80-a2ff-11e9-9239-599796bcd14f](https://github.com/ognimoddd/personal-budget/assets/77591203/e979e174-ca89-415e-83fa-9505b3486cf3)

![60954603-8ef08b80-a2ff-11e9-9d73-d0abae9f2625](https://github.com/ognimoddd/personal-budget/assets/77591203/90173833-1b17-4317-84c4-4ac6b27eb3e4)

![60954607-9021b880-a2ff-11e9-8831-586b989bfc6c](https://github.com/ognimoddd/personal-budget/assets/77591203/b260c882-ce2a-415c-9b56-968e067b73a3)

![60954608-9021b880-a2ff-11e9-8887-ee4cca96e350](https://github.com/ognimoddd/personal-budget/assets/77591203/90f2ce6e-667c-4563-83e7-7ad93d36741c)



