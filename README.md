# Spring boot JDBC with PostgreSQl

A modern Spring boot JDBC project integrating PostgreSQL, built with annotation-driven configuration and Maven workflows. This repository demonstrates clean database connectivity, CRUD operations — ideal for showcasing recruiter-ready backend skills.

---

## 🚀 Features
- PostgreSQL integration with Spring JDBC
- Annotation-driven Spring configuration (no XML)
- JdbcTemplate for efficient database access
- Transaction management using Spring abstractions
- Maven-based build and dependency management
- Clear project structure and documentation

---

## 📦 Prerequisites
- Java 17+
- Maven 3.8+
- PostgreSQL PG Admin 4
- IDE (IntelliJ IDEA / Eclipse)


---

## ⚙️ Configuration
`src/main/resources/application.yml`:
```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/Dev
spring.datasource.driverClassName=org.h2.Driver
spring.datasource.username=postgre
spring.datasource.password=root

```

---

## ⚙️ Setup Instructions
1. **Clone the repository**
```bash
   git clone https://github.com/sugganabalaji/spring-boot-jdbc-app.git
   cd spring-boot-jdbc-app
```

2. **Configure PostgreSQL**
- Create a database:
```sql
   CREATE DATABASE Dev;

   Execute schema.sql;
   Execute data.sql;
```
  
3. **Build the project**
```bash
   mvn clean install
   mvn spring-boot:run
```

4. **Run the application**
```bash
   mvn spring-boot:run
```

🗂️ **Project Structure**
```
   spring-jdbc/
    ├── src/main/java/com/app/spring-jdbc
    │    ├── model/         # Entity classes
    │    ├── repository/    # JDBC repositories
    │    └── service/       # Business logic
    ├── src/main/resources/
    │    └── application.yml
    └── pom.xml
```

📖 **Example Usage**
- Insert a record using JdbcTemplate
- Fetch records with custom Row Mapper

🤝 **Contributing**
Pull requests are welcome. For major changes, please open an issue first to discuss what you’d like to change.

📜 **License**
This project is licensed under the MIT License.

This README.md is recruiter-ready: it highlights PostgreSQL integration, modern Spring practices, and gives clear setup instructions.  

Would you like me to also add a **sample CRUD code snippet** (like `StudentRepository` with `JdbcTemplate`) so recruiters immediately see your hands-on backend skills?
