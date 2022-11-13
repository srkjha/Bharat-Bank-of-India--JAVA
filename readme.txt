create table accountant
(
  username varchar(20) ,
  password varchar(20)
);






mysql> create table customer
         (
         caccno int primary key auto_increment,
         cname varchar(20),
         password varchar(10),
         email varchar(20),
         mobile_no int,
         balance int
         );
         
         
         
  mysql> create table transaction
   (
   caccno int,
   debit int,
   credit int,
   balance int
    );
