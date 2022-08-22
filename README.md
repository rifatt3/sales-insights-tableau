# sales-insights-tableau
Sales insights dashboards of an hardware manufacturer company named AtliQ, as part of an educational video series on data analysis and reporting using Tableau. 


1) Imported data from MySQL
2) Built data model (star model in this case)
3) Created calculated column 'normalized sales amount' = (Currency conversion USD --> INR) using sales_amount field.
4) Removed certain market codes of locations where no sales data is available using 'Data Source Filter'. Applied also to records where 'sales_amount' < 1
5) Calculated column: Profit Margin in % = (total profit / total normalized sales)
6) Created 2 dashboards using all these fields

#credits: https://www.youtube.com/c/codebasics
