# ecommerce-bookworm
An e-commerce application for selling and buying product (book) online

## E-Commerce System (Focus on Books only - Bookworm shop)
<pre>
IMPORTANT: 
To run the website, the developer should go to MySQL and create a schema (database),
Then, from the MySQL, please import database's structure and data from the following folder
      ..\resources\bookworm.sql
to the created database.

IMPORTANT 2: 
The developer please goes to resources\application.properties
then change the database password to your current one in order to use it.

- The developer can run the website by accessing localhost:8080
- for login as admin account:
  admin8c@shopping.com
  123456
- for login as seller:
  seller@shopping.com
  123456
- for login as buyer:
  buyer@shopping.com
  123456
>> you can also go to the MySQL and run the query 'select * from `user`' to see the full list of
users
</pre>

## Technologies

<ul>
    <li>Spring boot MVC with thymeleaf + Rest API.</li>
    <li>Hibernate, lombok + JPA as ORM.</li>
    <li>MySQL as the database.</li>
    <li>Bootstrap 4.3.1 as layout and template.</li>
    <li>jQuery + ajax for client manipulate with rest api.</li>
    <li>Springboot Security as authentication & authorization.</li>
    <li>Springboot multipart support for upload file.</li>
</ul>

Technique
<ul>
    <li>XML config/Java Config</li>
    <li>PRG</li>
    <li>JSP, Thymeleaf</li>
    <li>Bean Validation or Spring Validator</li>
    <li>Custom Validation Annotation</li>
    <li>Custom Formatter</li>
    <li>Spring Security (Database, Logout, Remember Me, csrf, etc)</li>
    <li>Security authorization – interceptor, AOP</li>
    <li>Persistence – Hibernate + Spring Data</li>
    <li>CSS Library</li> 
</ul>


