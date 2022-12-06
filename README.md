# Small E_commerce Project 🛍
- REST API for Ecommerce_WebApplication is an WebApplication which Buy any kinds of Product with Payment Method Support.
- User can also check today, last week, last months and last few montsh as Jan - dec sales and sort the Product According to price and categories.

# Tech Stacks:
- Java
- Spring Boot
- Maven
- Swagger-Ui
- Lombok
- MySql
- SpringData Jpa
- Hibernate

# Modules
- Login, Logout Module
- Admin Module
- user Module

# Features
## Admin Features:
- Product List
- Add new products
- Manage Quantities
- Order management

# User Features:
- Landing Page
-Search functionality
- Search by category
- Sort, Filter by rating, price
- See individual product page
- Add to cart
- See cart details and total price in it
- Make a purchase, and track status
- See historical order
- Payment ,Checkout pages
-Login, Register Pages

# ER Diagram
The following Diagram depicts the flow of our Entity Relation Diagram to simplify the work flow.
![Swagger UI - Google Chrome 03-10-2022 09_20_51](https://github.com/nitish906/Ecommerce_WebApplication/blob/main/EcomorseApplication.png)

# Installation & Run
- Before running the API server, you should update the database config inside the application.properties file.

- Update the port number, username and password as per your local database config. server.port=8090

- spring.datasource.url=jdbc:mysql://localhost:3306/Gogreen spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver spring.datasource.username=mysql username - spring.datasource.password=YourPassword spring.jpa.hibernate.ddl-auto=update

- API Root Endpoint https://localhost:8090/

- http://localhost:8027/swagger-ui/

# Contributors
@Nitish Kumar
