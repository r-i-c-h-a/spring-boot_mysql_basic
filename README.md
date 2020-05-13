# mysql_basic

<h2>Create MySql database</h2>
<code>create database user_db;<br></code>
<code>create user 'mysql_access'@'%' identified by 'mysql123';<br></code>
<code>grant all on db_example.* to 'mysql_access'@'%';<br></code>

<h2>Build</h2>
<code>cd mysql-basic-functionalities<br></code>
<code>mvnw spring-boot:run<br></code>
