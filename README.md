# CRUD Operations in ASP.NET Core and SQL Server with Docker
CRUD Operations in as ASP.NET Core Docker app with SQL Server as a backend. Using Docker Compose for this so there will be 2 containers one running the ASP.NET Core app and other SQL Server 2019.

Once the SQL Server Container is up then connect with the SQL Server running in the docker container. So, in SQL Server Management Studio (SSMS), enter the following:

![204121831-b83d7095-b71d-41ee-b9ef-d000e9b6af10](https://user-images.githubusercontent.com/62908191/204122929-9116c628-f3bf-493d-bb58-1d987779c186.png)


localhost,1440 for the server name, recall 1440 was the port we set earlier. Instead of localhost we can also write your machine ip which we can get from running “ipconfig” command.
SA for login.
abD5r9tn0M@4 for password.
Click the Connect button to connect with this SQL Server running in the container.

Create MovieDB database and run "dbScript.sql" to create table.
