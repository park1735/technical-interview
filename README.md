# Introduction

Mimir Candidate,

Welcome to the technical interview for our project. The following ten open-ended questions are designed to evaluate your technical proficiency, critical thinking, reasoning, analytical abilities, and communication skills. We expect you to provide thorough and thoughtful responses that reflect your unique approach and expertise.


**Instructions:**

1. **Clone the Repository:**
    Begin by cloning the project repository from GitHub. This will be your working codebase for these exercises.
   
    a. done

2. **Create a New Readme.md**

   Describe your proficiency with the technologies used and/or referenced within this repository and these exercises.
   
   a.  I'm editing the current one.  I hope that you don't mind that.
   
   b.  My proficiency with technologies used and/or referenced within this repository and these exercises varries.
   
   c.  To begin with, the last time I used GitHub and Visual Studio was approximately 7 1/2 years ago when I worked on a contract with USCIS.  This was the last time that I had any experience using AWS, EC2, load 
       balancers and S3 buckets and until recently PostgreSQL.
   
   d.  After leaving the USCIS contract I landed at CBP supporting the Passenger Systems Program Directorate Land Border Integration division as part of a team conducting Anayses of Alternatives (AoA) for facial 
       recognition (FR) and license plate recognition (LPR) efforts.  Though I wasn't a developer or engineer on these efforts those skills served me well in working with the development teams.  Currently, we 
       support FR and LPR pilot/proof of concept efforts at various Ports of Entry across the United States and conduct ground-truthing efforts to measure the success and accuracy of these FR and LPR efforts.  We 
       also monitor and report on the performance of currently deployed LPR equipment.
   
   e.  This led to the creation of many queries in SQL Server for the pilot/proof of concept efforts along with queries in the Oracle production databases for monitoring and reporting on currently deployed 
       solutions and most recently PostgreSQL as CBP is migrating its databases from Oracle to PostgreSQL.

# Hands-On Coding Exercises: GitHub Project Upgrade

# Steps taken thus far: #

1.  Created GitHub account.
2.  Downloaded GitHub desktop.
3.  Cloned repository.
4.  Downloaded and installed Visual Studio 2022 Community Edition.
5.  Browsed for WeatherApp solution (.sln) files
    a. None were found
6.  Opened WeatherApp.Client .csproj file and attempted to run
    a.  Experienced errors indicating missing WeatherApp.Shared.csproj file
    b.  WeatherApp.Shared .dll was referenced under Projects branch of Dependencies
    c.  Added WeatherApp.Shared to the solution and code would run
    d.  However, browser tab that opened in default web browser was non-functional
7.  After getting this solution to run (at a bare minimum), I forked the changes back to my GitHub repository
8.  


3. **Make Your Changes:** 

   Select a minimum of four exercises from the below list for this interview process. For each of the exercises that you select, make the necessary modifications directly in the code. As you work, document your changes by including clear explanations (within your new readme.md file) that describe **how** you implemented your solution and **why** you chose that particular approach. 

4. **Submit Your Solution:** 

   After completing all the exercises, upload the updated private repository to your personal GitHub account. Then, email us the private repository link along with your explanations. Your submission will be reviewed for coding efficiency, technical proficiency, and the clarity of your documentation.

Good luck!

---

## 1. Solution Architect Experience

Clone the project and review its overall architecture. Implement changes to enhance scalability—such as integrating a caching layer or restructuring into a multi-tier architecture. Document your approach, explaining your design decisions and how these changes improve scalability and maintainability.
 
---

## 2. Database Implementation

Examine the current database implementation and upgrade the data-access layer. Consider refactoring it to better utilize an ORM or improve the existing schema design. Modify the code accordingly and include a detailed explanation of your changes and the reasoning behind them.

---

## 3. Database Performance for Postgres

Identify one or more queries interacting with the Postgres database that could be optimized. Enhance their performance by refactoring the query logic, adding indexes, or implementing partitioning strategies. Update the project, and provide documentation on the performance improvements and your approach.

---

## 4. Design Patterns

Select a section of the code (such as controllers, services, or repositories) that could benefit from a specific design pattern (e.g., Repository, Factory, or Strategy). Refactor the code to incorporate this design pattern. Explain your choice, how you implemented it, and the benefits it brings to the project.

---

## 5. C#.NET Core Enhancements

Review the backend C#.NET Core code and implement enhancements to improve performance and maintainability. This might include leveraging asynchronous programming, custom middleware, or newer language features. Modify the code and document your implementation process and the rationale behind your decisions.

---

## 6. MVC Dependency Injection

Analyze the current usage of dependency injection within the MVC framework in this project. Identify areas where DI can be better applied, refactor the code to enforce proper DI practices, and provide a summary of your modifications and the benefits achieved through better decoupling and testability.

---

## 7. HTML/CSS Mixed UX Experience

Evaluate the user interface built with HTML/CSS and implement enhancements to improve responsiveness and overall user experience. Update the UI for better accessibility and visual consistency across devices. Document your changes and explain your design choices.

---

## 8. OOP C# Advanced Reasoning Skills

Identify one or more classes where object-oriented principles (like encapsulation, polymorphism, or adherence to SOLID principles) could be improved. Refactor these classes to enhance their design and functionality. Include an explanation of the refactoring process and the benefits of your approach.

---

## 9. JavaScript Enhancements

Review the client-side JavaScript code and add an interactive feature or refactor existing functionality to improve modularity and maintainability. Make the necessary code changes and provide documentation on how and why your enhancements improve the overall project.

---

## 10. RESTful APIs and JSON

Examine the current RESTful API endpoints and implement improvements to enhance efficiency, security, or functionality. For example, update an endpoint to return JSON data with improved validation and error handling. Modify the project accordingly and document your approach and rationale.

---
