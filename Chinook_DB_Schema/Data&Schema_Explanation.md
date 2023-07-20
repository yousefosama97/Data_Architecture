# Goal & Objective
  
Introduce an example of a database schema to demonstrate how data can be organized and related in tables. Designing a database schema


## Database schema design 

Before you develop your actual database, you should design a relevant database schema to document the requirements and to propose an architecture of the database structure. 
To design a basic database schema, you need to apply the following steps:  

__Step 1__: Define the database purpose.  

__Step 2__: Identify the database tables including 

  * Tables attributes 

  * Attributes data types 

  * Primary key for each table  

__Step 3__: Create relationships between tables


## Instructions 


* Task 1: Identify the database purposes.  

* Task 2: Identify 6 main tables with a brief description and a primary key for each table.  

* Task 3: Identify the relationships between the 6 main tables. 

* Task 4: Create an entity relationship diagram of the 6 main tables. 

# Solution

* Task 1: Identify the database purpose 

  The “chinook sample” database represents a fictitious digital media company that includes information about artists, albums, media tracks, invoices and customers. 

* Task 2: Identify the database tables 

  The chinook sample database has considered adequate normalization level and created 11 tables to store and relate data to avoid data redundancy. However, this exercise will only focus on 6 main tables, including some relevant attributes for each.  

|Table name | Description  | Diagram |  
|----------|-----|-----------------|
|Employees |The employee table stores the data of all employees. <br> The diagram presents 8 attributes with relevant datatypes. <br> Employee ID is the primary key in this table. |1|
|Customers | The customer table stores customers data. <br> In the diagram, 8 attributes with relevant datatypes are presented. <br> Customer ID is the primary key in this table. |2|
|Invoices | The invoice table stores data on invoices.<br> In the diagram, 5 attributes with relevant datatypes are presented. <br> Invoice ID is the primary key in this table. |3|
|Artists | The artist table stores data on artists. <br> Only 2 attributes, the artist ID and artist name, are presented in the diagram alongside their relevant data types.<br>Artists ID is the primary key in this table.|4|
|Albums | The album table stores data about a list of tracks. <br> In the diagram, 3 attributes with relevant data types are presented. <br> Album ID is the primary key in this table. |5|
|Tracks | The tracks table stores the data of songs. <br>In the diagram there are 5 attributes with relevant data types. <br>Tracks ID is the primary key in this table.|6|

 

* Task 3: Identify relationships between tables 

   - The chinook sample database defines the following relationships between the 6 stated tables:  

   - Each employee will support one or many customers.  

   - Each customer may have multiple invoices  

   - Each track belongs to one album. 

   - Each invoice relates to one track. 

   - Each track belongs to one album  

   - Each album may contain multiple tracks 

   - Each artist has one or multiple albums 


* Task 4: Create entity relationship diagram 

In Images attached
