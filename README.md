# Postgresql
postgresql_homeworks
SELECT description , length FROM film
WHERE NOT length > 50 AND rental_rate = 2.99 OR rental_rate = 4.99 ;

SELECT first_name, last_name FROM customer
WHERE first_name = 'Mary' ;

SELECT title , description , rental_rate , replacement_cost FROM film
WHERE rental_rate = 0.99 AND replacement_cost = 12.99 OR replacement_cost = 28.99 ;

SELECT title , description FROM film
