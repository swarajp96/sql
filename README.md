# sql
sql asssignment
Assignment
Table 1: SalesPeople 
Snum is Primary key 
Sname is Unique constraint 
Snum Sname City Comm
1001 Peel. London .12 
1002 Serres Sanjose .13 
1004 Motika London .11 
1007 Rifkin Barcelona .15 
1003 Axelrod Newyork .10 
Table 2: Customers
Cnum is Primary Key 
City has not null constraint . 
Snum is foreign key constraint refers Snum column of SalesPeople table. 
Cnum Cname City Snum
2001 Hoffman London 1001 
2002 Giovanni Rome 1003 
2003 Liu Sanjose 1002 
2004 Grass Berlin 1002 
2006 Clemens London 1001 
2008 Cisneros Sanjose 1007 
2007 Pereira Rome 1004 
Table 3: Orders
Onum is Primary key 
Cnum is foreign key refers to Cnum column of Customers table. Snum is foreign key refers Snum 
