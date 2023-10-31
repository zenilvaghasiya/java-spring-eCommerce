# java-spring-eCommerce
# Quickstart

Clone the repository
Open the project in your IDE: IntelliJ IDEA (recommended) or Eclipse
If you are using IntelliJ IDEA, make sure the IDE recognizes the project as a Spring Boot project. Also, you must change the working directory of the project so that the views (the actual web pages to be shown) are found by Spring Boot (check out Web Directories IntelliJ IDEA.
Make sure you are in the JtProject directory
Configure the database connection in application.properties file (check the Database section below for more info)
Run the project (by running the main method in JtSpringProjectApplication.java)
Open http://localhost:8080/ in your browser!
If you ran the basedata.sqlscript on the database, you can log in with the following credentials as admin; otherwise you'll have to manually create an admin user in the database:
Username: admin
Password: 123
Log in as a normal user:
Username: lisa
Password: 765

# Database
MySQL or MariaDB can be used as the database for this project. The database connection can be configured in the application.properties file, with the appropriate values for the following properties:

    db.url=jdbc:mysql://[ip address of db]:[port of db]/ecommjava?createDatabaseIfNotExist=true
    db.username=[username]
    db.password=[password, if any]


<img width="812" alt="Screenshot 2023-10-31 at 1 11 56 AM" src="https://github.com/zenilvaghasiya/java-spring-eCommerce/assets/47736398/d32962a0-0cbb-4e56-8860-7e8ffc6965fb">
<img width="830" alt="Screenshot 2023-10-31 at 1 11 43 AM" src="https://github.com/zenilvaghasiya/java-spring-eCommerce/assets/47736398/fbe88647-f602-468b-9fc1-f3ec843670f3">
<img width="815" alt="Screenshot 2023-10-31 at 1 11 26 AM" src="https://github.com/zenilvaghasiya/java-spring-eCommerce/assets/47736398/9d992f3a-a229-4f8f-b544-6e10cabb4449">
