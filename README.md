# 08. EngineeringPortfolio.Web

# Engineering Portfolio – ASP.NET MVC

## Overview
This portfolio website is built using ASP.NET MVC and C#.  
It is designed to showcase practical software engineering skills, including clean architecture, backend development, 
unit testing, and cloud deployment on Azure.


## Tech Stack
- ASP.NET MVC (.NET 8)
- C#
- Entity Framework Core
- SQL Server
- xUnit & Moq (for unit testing)
- Azure App Service
- GitHub Actions (CI/CD)

## Architecture
The website uses a layered architecture to keep the code clean and maintainable:

- **Controllers** – Handle HTTP requests and send responses to the views  
- **Services** – Contain business logic, making the system testable  
- **Repositories** – Manage data access and communicate with the database  
- **Data Layer (EF Core)** – Handles database models and migrations  

This structure ensures separation of concerns and makes the application easier to maintain and extend.
