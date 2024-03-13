# Zomato Portfolio Project

This portfolio project involves analyzing Zomato customer data using SQL queries. The project includes various queries to extract insights such as customer spending, visit frequency, popular items, and more.

##Data Overview
| Column           | Description                                     | Data Type  |
|------------------|-------------------------------------------------|------------|
| userid           | Unique identifier for users                     | INTEGER    |
| signup_date      | Date when the user signed up                    | DATE       |
| product_id       | Unique identifier for products                  | INTEGER    |
| created_date     | Date when the sales transaction occurred        | DATE       |
| gold_signup_date | Date when the user upgraded to gold membership  | DATE       |
| product_name     | Name of the product                             | TEXT       |
| price            | Price of the product                            | INTEGER    |


## Instructions
- Set up a MySQL database and execute the provided SQL script to create tables and insert sample data.
- Run the SQL queries provided in the script to analyze the data and derive insights.

## SQL Queries
- Query 1: Total amount spent by each customer on Zomato.
- Query 2: Number of days each customer visited Zomato.
- Query 3: First product purchased by each customer.
- Query 4: Most purchased item and its frequency.
- Query 5: Most popular item for each customer.
- Query 6: First item purchased after becoming a gold member.
- Query 7: Last item purchased before becoming a gold member.
- Query 8: Total orders and amount spent by each member before becoming a gold member.
- Query 9: Calculate points collected by each customer and the product with the most points.
- Query 10: Points earnings in the first year for customers in the gold program.
- Query 11: Rank all transactions of the customers.
- Query 12: Rank all transactions for each member, marking non-gold member transactions as 'na'.

## Dependencies
- MySQL database

## Usage
1. Set up a MySQL database.
2. Execute the provided SQL script to create tables and insert sample data.
3. Run the SQL queries in your MySQL client to analyze the Zomato customer data.



