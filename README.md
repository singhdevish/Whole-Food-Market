# Whole Foods Market Retail Strategy Revamp in India

## Project Overview
Whole Foods Market, a multinational company, is looking to revamp their retail strategy in India. As a Data Analyst, I have been assigned to provide analytical support to the business in making these critical decisions. My role involves analyzing data related to orders placed at various locations in India, customer information, and returns.

## Data Description
The data has been loaded into a MySQL and SQL Server database and consists of the following tables:

### `orders` Table
- **Order_ID** (VARCHAR): Primary key for each order placed
- **Order_Date** (VARCHAR): Date when the order was placed
- **Ship_Date** (VARCHAR): Date when the order was shipped
- **Customer_ID** (VARCHAR): ID of the customer who placed the order
- **Segment** (VARCHAR): Segment to which the product sold belongs
- **State** (VARCHAR): State where the order was placed
- **City** (VARCHAR): City where the order was placed
- **Product_ID** (VARCHAR): ID of the product sold
- **Category** (VARCHAR): Category of the product sold
- **SubCategory** (VARCHAR): Subcategory of the product sold
- **Product_Name** (VARCHAR): Name of the product sold
- **Sales** (DOUBLE): Sale price of the order
- **Quantity** (DOUBLE): Quantity of the product for which the order was placed
- **Discount** (DOUBLE): Percentage discount offered on the MRP
- **Profit** (DOUBLE): Total profit made on the order

### `customers` Table
- **Customer_ID** (VARCHAR): ID of the customer, primary key of the table
- **Customer_Name_** (VARCHAR): Name of the Customer

### `returns` Table
- **Order_ID** (VARCHAR): Primary key of the order returned
- **Returned** (VARCHAR): Indicates if the order was returned or not

## Objective
Objective is to write SQL queries to analyze the provided data and provide valuable insights to Whole Foods Market. These insights will help the company make informed decisions to revamp their retail strategy in India.
