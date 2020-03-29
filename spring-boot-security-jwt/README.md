How to use login process

The application showing how to use Spring Boot with Spring Security for common needs, such as:

Customized login form
DAO-based authentication
Basic "remember me" authentication


links -> http://localhost:8080/authenticate, using this url with username and passowrd  

links -> localhost:8182/actuator/health

INSERT INTO user (id, password, username) VALUES (1, '$2a$10$o8/9MyCNyOvSsuaUXS9nV.0JeTPjow/Xlr7qk9iod9OBi0LsLkX9m', 'karuna');
INSERT INTO user (id, password, username) VALUES (2, '$2a$10$neLHNssqGcVqamdyuVTQcOC/x4unq3spy1AGAbhrND73R2OIpXouS', 'admin');

you can write data below first-three sql queries instead of above sql queris in src/main/resources/data.sql

INSERT INTO USERS VALUES('user1','{bcrypt}$2a$10$FMQOTEUiRN1L2MV2gfYas.MEDnLcEffuenRme5WdFgkwcuWA2jyhG',TRUE);
INSERT INTO USERS VALUES('user2','{bcrypt}$2a$10$.qPu/z1bV0Lw5uSpv6YMKeiCUI4rsxfNY/HJJBgw9E7CYUULMW3CS',TRUE);
INSERT INTO USERS VALUES('celal','{bcrypt}$2a$10$m9RM8vLgWvu/8Ig21HURG.IHIeFEie8CsKaGV1FeQ88bi27Xz4wJS',TRUE);

username and password will be same again when you changed first-three lines in src/main/resources/data.sql.


for example (encrypted data)

12345 -> {bcrypt}$2a$10$FMQOTEUiRN1L2MV2gfYas.MEDnLcEffuenRme5WdFgkwcuWA2jyhG
secrett -> {bcrypt}$2a$10$.qPu/z1bV0Lw5uSpv6YMKeiCUI4rsxfNY/HJJBgw9E7CYUULMW3CS
secret -> {bcrypt}$2a$10$m9RM8vLgWvu/8Ig21HURG.IHIeFEie8CsKaGV1FeQ88bi27Xz4wJS