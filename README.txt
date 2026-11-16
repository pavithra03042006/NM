HOW TO USE
1. Create project in https://start.spring.io (Maven, Java 17, Spring Boot 3.x, Jar).
2. Open an EX_xx.txt file, copy everything, paste into
   src/main/java/com/example/demo/DemoApplication.java (replace all).
   (Files are .txt because every program uses the class name DemoApplication.)

DEPENDENCIES (Initializr)
 EX_01, EX_02, EX_03        : Spring Web
 EX_04 to EX_09, EX_11-15   : Spring Web, Spring Data JPA, H2 Database
 EX_10                      : Spring Web, Aspect Oriented Programming (AOP)

application.properties (JPA experiments only)
 spring.datasource.url=jdbc:h2:mem:testdb
 spring.jpa.hibernate.ddl-auto=update
 spring.jpa.show-sql=true

TEST URLs
 01 /ioc            02 / and /hello     03 /hello
 04 /add/Ravi/CSE then /sort and /page/0/2
 05 /add/Ravi/CSE then /name/Ravi, /dept/CSE, /start/Ra
 06 /add/Ravi/CSE, /update/1/Kumar, /all
 07 /add/Ravi/CSE, /custom/CSE
 08 /add, /all, /get/1, /update/1/Kumar, /delete/1
 09 /book/Madurai/Chennai, /all, /source/Madurai, /cancel/1
 10 /hello (watch the console)
 11-15 Postman: POST/GET/PUT/DELETE on /coach, /train, /ticket, /guess, /movie
