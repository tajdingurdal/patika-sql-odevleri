 
# Odev8

- CREATE TABLE employee( id SERIAL PRIMARY KEY, name VARCHAR(50), birthday DATE, email VARCHAR(100) );
- insert into employee (name, email, birthday) values ('Hughie', 'hbushell0@nytimes.com', '1991-11-29'); 50 adet veri buna benzer şekilde eklendi.
- 5 adet güncelleme işlemi :
````
UPDATE employee SET name = 'deneme1' WHERE id = '1'; 
UPDATE employee SET name = 'deneme2' WHERE id = '2';
UPDATE employee SET name = 'deneme3' WHERE id = '3';
UPDATE employee SET name = 'deneme4' WHERE id = '4';
UPDATE employee SET name = 'deneme5' WHERE id = '5';
````

- 5 adet silme işlemi 

````
DELETE FROM employee WHERE name = 'deneme1';
DELETE FROM employee WHERE name = 'deneme2';
DELETE FROM employee WHERE name = 'deneme3';
DELETE FROM employee WHERE name = 'deneme4';
DELETE FROM employee WHERE name = 'deneme5';
````