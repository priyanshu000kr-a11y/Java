# SmartStudent
Java + JDBC + MySQL console Student Management System.

Features: static admin login, add/view/update/delete, search by roll/name/department, marks filter, statistics, input validation.

Login: admin / admin123

Setup: run student.sql, install MySQL Connector/J, replace YOUR_MYSQL_PASSWORD in DatabaseConnection.java.

Windows compile: javac -cp ".;mysql-connector-j-<version>.jar" *.java
Run: java -cp ".;mysql-connector-j-<version>.jar" Main
