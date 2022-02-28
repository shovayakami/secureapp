# Overview
<b>Secure App</b> is an application built in `Spring Boot`. It has a login screen, registration screen and the landing page. The UI is built using `Thymeleaf`.

## How to run the application
To run the application it needs a database connection. Here is what you need.

* Create a database named `secureapp` in MySQL.
* Set username as `user`
* Set password as `password`
* These are the connections that I've mentioned in the `application.properties` file.

### Running Application

* Run/Debug `SecureappApplication`.
* The application starts in the port 8080.
* Launch the application in the browser: http://localhost:8080/
* You will see the login page. As you don't have any users registered yet, you need to register the users first by going into the registration page.
* Before registering the users insert `role_id` as 1 and `role` as ADMIN in the `roles` table. I'm assigning the role of ADMIN to the new users.
* Now register the users by providing `name`, `last name`, `email`, `username`, and `password`.
* Once the registration is successful, you can log in using the same `username` and `password`.
* After log in, you can use <b>swagger ui</b>: http://localhost:8080/swagger-ui/index.html

