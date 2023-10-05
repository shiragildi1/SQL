# SQLThe goal is: to manipulate a database schema for an election-related system. Below is a breakdown of the script:
a) Creating tables:
Four tables - elections, party, city and competition. Each of them includes the fields and defines a primary key for it.

b) Creating a trigger:
You have created a function called trigf1. The function goes through the data in the running table and updates the totalvotes field for the party according to the trigger since it is activated with each entry or new update in the votes table. The T1 trigger is created and activated according to the trigf1 function when entering data into the voting table.

c) Entering data into the tables:
Entering data into the election, party, city and running tables using INSERT INTO.

d) SQL queries:
Chapter D includes a number of SQL queries in which various operations are performed on the data of the tables. Each query is marked with a d and briefly explained what it does.
