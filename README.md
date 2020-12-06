# Sales-Analysis-Map-Reduce

There is an E-commerce company spanned over multiple countries. The manager wants to know the total sales in each country from the data available from different companies. This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers."

I have taken dataset from Kaggle.com

Solution: The solution is straightforward.Mapper will generate key value pairs with country name as key and quantity as value for each invoice. Reducer will receive items grouped  by country and count the total quantity sold in that country.
