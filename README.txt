INSTALL:

In case you don't know how to install this .sql file,

a. in phpMyAdmin
Create a database and then import quotesdb.sql.

b. from the command line
Login to mysql: mysql -uroot -ppassword
Create database: CREATE DATABASE quotesdb;

Just pipe to mysql with

mysql -uroot -ppassword quotesdb < quotesdb.sql

.
Enjoy!
