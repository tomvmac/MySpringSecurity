To access the login page, enter the following URL:
http://localhost:8081/spring-security-ldap-embedded/krams/auth/login
http://localhost:8080/krams/auth/login
To logout, enter the following URL:
http://localhost:8081/spring-security-ldap-embedded/krams/auth/logout
To access the admin page, enter the following URL:
http://localhost:8081/spring-security-ldap-embedded/krams/main/admin
To access the common page, enter the following URL:
http://localhost:8081/spring-security-ldap-embedded/krams/main/common
Here are the usernames and passwords:
rbrowning - pass
jkeats - pass
hwilliams - pass
jmilton - pass

That's it. We've managed to setup a simple Spring MVC 3 application, that's secured by Spring Security. We also used an embedded LDAP server for authenticating our users.

The best way to learn further is to try the actual application.

Download the project
You can access the project site at Google's Project Hosting at http://code.google.com/p/spring-security-ldap/

You can download the project as a Maven build. Look for the spring-security-ldap-embedded.zip in the Download sections.

You can run the project directly using an embedded server via Maven.
For Tomcat: mvn tomcat:run
For Jetty: mvn jetty:run