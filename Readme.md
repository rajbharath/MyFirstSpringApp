My First Spring Web application:
=================================
This is my first spring application. I thank to Spring boot guide.

Description:
------------
This application has one controller(HelloController) class and the Application class(which has main method).
Running this application prints all the default bean names of spring boot application and current application beans as well (hellocontroller is considered as one of the bean)

Since Hello Controller is annotated as @RestController, it is accessible from localhost:8080.

I have written two url mapping in this controller

    1. localhost:8080/ -  this will return the data as "Greetings from Spring boot"
    2. localhost:8080/hi - this will return the data as "Hi"






