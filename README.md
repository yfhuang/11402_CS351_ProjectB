# Project B - CSV Mini Database and Query Engine

Project B focuses on building a lightweight database system that stores data in CSV files and executes simple query operations on top of them. The goal is to treat plain CSV datasets as database tables, then implement a small query engine that can load data, interpret user commands, and return filtered or transformed results.

The project is intended to model the core ideas behind a relational database at a smaller scale. Instead of relying on a full database server, the system works directly with CSV files and provides basic database behaviors such as reading tables, selecting columns, filtering rows, and producing query results in a structured format.

At a high level, the system should support:

- Loading one or more CSV files as tables
- Parsing and executing a limited query language or command set
- Selecting specific attributes from a table
- Applying conditions to filter matching rows
- Displaying query results clearly and consistently

This project emphasizes data parsing, internal representation of tabular data, and the design of a simple execution pipeline for queries. The final result is a mini database engine that demonstrates how structured data can be stored, searched, and queried without a full-scale DBMS.



