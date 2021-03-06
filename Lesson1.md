# Lesson 1: Retrieving Data

In this class, students will be introduced to relational data terminology (row, column), the function of a primary key, and retrieving data from a MySQL database using SELECT queries.

Objective: Students should be able to retrieve data from a database table using SELECT statements that include WHERE, GROUP BY, and ORDER BY.

## Pre-Class Readings

- [What are databases?](https://www.youtube.com/watch?v=Ls_LzOZ7x0c)
- [Exploring databases and database management systems](https://www.youtube.com/watch?v=7jsWu7ONSNg&list=PLYlr48f6CaXtlkXcGMUD49wHmvC7ZTiD0&index=4)
- [The features of a relational database](https://www.youtube.com/watch?v=6fojQYSOSB4&list=PLYlr48f6CaXtlkXcGMUD49wHmvC7ZTiD0&index=5)
- [Introduction to database modeling](https://www.youtube.com/watch?v=rBCXhbA3hPg&list=PLYlr48f6CaXtlkXcGMUD49wHmvC7ZTiD0&index=11)
- [SQL: Using the basic SELECT statement](https://www.youtube.com/watch?v=4hU3K8Gm0YM&index=12&list=PLcVWkhzl1ZGRERTB2vEN5vepWZaYuoSTz)
- [Creating SQL queries](https://www.youtube.com/watch?v=uR2hDQvM9Bo&list=PLYlr48f6CaXtlkXcGMUD49wHmvC7ZTiD0&index=26)
- [Creating the WHERE clause](https://www.youtube.com/watch?v=5KY2Ci0UWe8&index=27&list=PLYlr48f6CaXtlkXcGMUD49wHmvC7ZTiD0)
- [Sorting query results](https://www.youtube.com/watch?v=VYyEZHTx-3c&list=PLYlr48f6CaXtlkXcGMUD49wHmvC7ZTiD0&index=28)
- [Using aggregate function](https://www.youtube.com/watch?v=r1TsKlGXes0&list=PLYlr48f6CaXtlkXcGMUD49wHmvC7ZTiD0&index=29)
- [Joining tables](https://www.youtube.com/watch?v=8Mo2ka8PSpw&list=PLYlr48f6CaXtlkXcGMUD49wHmvC7ZTiD0&index=30)


## Main Topics

- The relational model of data
- A 'database' vs. a 'DBMS' (database management system)
- The concept of a schema
- The properties of an 'entity' (or 'row')
- Basic entity relationship diagrams
- A basic SELECT statement
- Constructing more complex SELECT statements
- JOIN
    - Selecting composite data from multiple tables
    - Compare JOIN WHERE with cartesian product
- Naming Conventions: UpperCamelCase/PascalCase, lowerCamelCase, snake_case, hnHungarianNotation/HNHungarianNotation
- Character Sets in Databases (hint: always use UTF-8 encoding, called 'utf8mb4' in MySQL)


## Reference Material

- [TutorialsPoint MySQL Introduction](http://www.tutorialspoint.com/mysql/mysql-introduction.htm)
- [Official MySQL Documentation](https://dev.mysql.com/doc/refman/5.7/en/)
- [Official MySQL Tutorial (pretty dense)](https://dev.mysql.com/doc/refman/5.7/en/tutorial.html)
- [Node MySQL Documentation on Github](https://github.com/mysqljs/mysql)
- [Types of SQL JOINs](http://www.khankennels.com/blog/index.php/archives/2007/04/20/getting-joins/)
- [Joel Spolsky - Character Sets and Unicode](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/)

## Homework

Design queries that retrieve the following data sets. Compare with classmates to see if your answers were correct.

- Find out how many todo items are on the list
- Find all the todo items that are marked as done
- Find all the todo items that are not marked as done
- Get all the todo items, sorted with the most recent first
- Get the single most recently added todo item
- Get all todo items about 'databases'

Build a simple Node application to connect to the class database (using `require('mysql')`). Run the above SQL statements through your Node app (either command-line input or hard-coded) and print the results on the command line.
