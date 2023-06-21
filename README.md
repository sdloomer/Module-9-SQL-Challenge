1. Data Modeling
--
After going through each of the six CSV files and noting all shared columns, I created an ERD using QuickDBD. I noticed two columns were especially prolific in the CSVs: "dept_no" and "emp_no" and adjusted the diagram accordingly. This diagram is attached as a .png file.

2. Data Engineering
--
Using the ERD, I then created table schemata for each CSV, specifying primary keys and referencing them where necessary, foreign keys, and other constraints such as "NOT NULL" and defining data types and value lengths for each column. Because foreign keys of a table need to reference tables created before, I created the schemas in an order that seemed appropriate, and imported the CSV files in that same order.

3. Data Analysis
--
Using the analysis guidelines, I used Postgres to input my queries for the tables to show the output correctly.