# Session26---Assignment26_1--Assignment-1
DATA ANALYTICS WITH R, EXCEL AND TABLEAU SESSION 26 ASSIGNMENT 1

SESSION 10: RDBMS (CONTD.)
Assignment 1
4. Associated Data Files Use the Sakila schema, which can be found in following link (to be installed in your local system) 
http://dev.mysql.com/doc/index-other.html("sakila database") 
http://dev.mysql.com/doc/sakila/en/sakila.html(for full documentation) 
 
Requirements 
For each question, you are required to provide the following: 
- The SQL query you used 
- The answers 
- Any assumptions you made 
5. Problem Statement
 1. What are the names of all the countries in the databases which start with the letter "B" (sorted by their names)?  
2. Return the first names (sorted) of all the actors with the last name "berry".  
3. Find all the films whose length is more than 184 (inclusive). Order the results by the length (and for films with the same length order them by their name). Return their title and the length.
Ans:-
26.1.1
Question:  What are the names of all the countries in the databases which start with the letter "B" (sorted by their names)?

Select country from country where country like 'B%' order by country;

=====================
26.1.2
Question: Return the first names (sorted) of all the actors with the last name "berry".

Select first_name from actor where last_name='berry' order by first_name;

======================
26.1.3
Question: Find all the films whose length is more than 184 (inclusive). Order the results by the length (and for films with the same length order them by their name). Return their title and the length.

Select title,length from film where length>=184 order by length,title;

Output:-
 
 
 
