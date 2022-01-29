# sales_data_analysis-with-SQL


### Data Analysis Using SQL


1. Show all records

   `SELECT * FROM sale_data;`
   
1. Show Total number of records in table

     `SELECT count(*) FROM sale_data;`
     
1. Show TotalPayment for only may(05) month
   
   `SELECT * FROM sale_data where InvoiceDate LIKE '2020-05-__ 00:00:00'`
   
1. show sum of TotalPayment for may month

   `SELECT SUM(DISTINCT TotalPayment) AS "Total payment"
   FROM sale_data
   where InvoiceDate LIKE '2020-05-__ 00:00:00'` 
   
1. From above Formula we can also find TotalPayment for June, July, August, september, October, November, december, january(2021) and februar(2021).

1. From this data we can compare sum of TotalPayment of every months.
    
