#### Structured Query Language
- SQL is used to perform operations on Relational DBMS
- SQL is declarative (programs specify what is to be done.)

1) **CREATE:**  
  CREATE TABLE table_name (
  column1 type1,
  column2 type2,
  ...);

2) **INSERT:**   
     INSERT INTO  
    table_name (column1, column2,..., columnN)  
    VALUES  
    (value11, value12,..., value1N),  
    (value21, value22,..., value2N),  
    ...;

 3) **RETRIEVE:**   
      SELECT * 
FROM table_name    
WHERE condition;

4) **UPDATE:**  (updates the data of an existing table in the database)   
     UPDATE table_name    
     SET column1 = value1;

5) **DELETE:**    
     DELETE FROM table_name    
     WHERE column1 = value1;

6) **ALTER:**  (alters the layout of the table; modifies existing columns in a table)   
     - add column:   
         ALTER TABLE table_name  
         ADD column_name datatype;
    - rename column:   
        ALTER TABLE table_name   
        RENAME column c1 TO c2;
    - drop column:  
        ALTER TABLE table_name   
        DROP COLUMN column_name;
