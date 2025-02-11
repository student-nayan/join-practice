# join-practice
*COMPANY* : CODETECH IT SOLUTION

*NAME* : NAYAN GANGADHAR MOTE

*INTERN ID*: CT08RLF

*DOMAIN* : SQL

*DURATION* : 4 WEEKS

*MENTOR* : NEELA SANTHOSH KUMAR

*DESCRIPTION*: ### *Understanding SQL Joins and Their Real-World Applications (Using MySQL)*  

In the world of databases, data is often stored in multiple tables to keep things organized and avoid redundancy. However, there are times when we need to pull information from different tables and combine it to get a complete picture. This is where *SQL Joins* come into play. SQL Joins allow us to merge data from two or more tables based on a common field, making it easier to analyze and extract meaningful insights.  

For this task, I used *MySQL*, a widely used relational database management system (RDBMS) known for its speed, reliability, and ease of use. MySQL is commonly used in web applications, businesses, and enterprise-level data management due to its efficiency in handling structured data.  

There are different types of SQL Joins, each serving a specific purpose. The *INNER JOIN* retrieves only the records that have matching values in both tables. This is useful when we want to see data that is connected in both tables, such as employees and their respective departments. The *LEFT JOIN* returns all records from the left table and only the matching records from the right table. If there is no match, the result will include NULL values. This is helpful when we want to find, for example, all employees, even those who have not been assigned a department. The *RIGHT JOIN* works similarly but returns all records from the right table and only the matching ones from the left. Finally, the *FULL JOIN* brings in all records from both tables, filling in NULL values where there is no match. However, since *MySQL does not support FULL JOIN, we can achieve the same result by using a **UNION* of LEFT and RIGHT JOIN queries.  

*OUTPUT*:
