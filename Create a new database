# MYSQL

how to create new database.

/*show the list of available databases*/
show databases;


/*create a new database*/
Create database db_sandy;

/*check whether the new database has been created or not*/
show databases;

/*delete db_sandy database*/
drop database db_sandy;

/*_ _ _ _ _ _ _ _ _ _ _ _*/
/*create training database*/
create database training;

/*create database list*/
show databases;

/*create emp table in training database*/
create table training.emp (id int primary key,name varchar(20) not null,age int);

/*check emp table in training database*/
use training; /*to get inside training database*/
show tables; /*to show the list of tables from the database*/

/*insert data into emp table*/
Insert into training.emp
(id,name,age)values
(4,'jim',20),
(2,'kim',18),
(3,'tin',14);


/*show data from training.emp*/
select  * from training.emp;


/*Add gender column*/
Alter table training.emp
add column gender varchar(5) after age;

select * from training.emp;

/*update gender for is 1*/
update training.emp
set gender= 'R'
where id=1;

/*Delete record for id 3*/
Delete from training.emp
where id=3;

/*Delete all the records from the table emp*/
truncate training.emp;

Select  * from training.emp;


/*Delete column gender from emp table*/
Alter table training.emp
drop column gender;


/*Create view of emp data excluding age*/
create view training.emp2
as
select id, name from training.emp;

select * from training.emp2;

/*Create a temporary table*/
create temporary table training.emp3
as
Select * from training.emp;

select * from training.emp3;

use training;
show tables;

/*check table structure*/
describe training.emp;











