# microservices

There are 3 different micro services defined in this project.

1)ms-registration : This service acts as the registration server.
2)ms-web : client service
3)ms-accounts client service

URLs to access this application:

Starting point - http://localhost:3333
To see the status of registered services - http://localhost:1111  

To build and run the application/micro services:

1) Open windows command terminal and login to microservices folder.
2) Build the application using mavne command "mvn package".
3) Open three command terminals to start three services.
4) In Terminal1 - Run, microservices/ms-registration>java -jar target\registration.jar
5) In Terminal2 - Run, microservices/ms-web>java -jar target\web.jar
6) In Terminal3 - Run, microservices/ms-accounts>java -jar target\accounts.jar