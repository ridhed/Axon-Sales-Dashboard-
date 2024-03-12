# Axon Classic Vehicles Sales Dashboard

## 1. Cover page

### Insights
- Axon company has sold 106k vehicles for a total of $8.85 million, indicating that the average order value is $2.96 thousand.
- There are a total of 2996 customers who purchased those vehicles and placed a total of 2996 orders.

## 2. Sales Overview

### Charts and Insights

#### i. Sales by Country Map Visualization
- The United States is the top country for sales, followed by France, UK, Australia, and Japan.

#### ii. Sales Trend Timeline
- Sales appear to be increasing over time from 2003 to 2004, with the highest sales. However, the sales drastically decreased in the year 2005.
- The drastic fall in car sales in the year 2005 could be due to a surge in gasoline prices.

#### iii. Sales vs Profit Chart
- Sales and Profit were directly proportional to each other.
- Sales increased by 32.71% from 2003 to 2004, however, the sales drastically decreased by -70.09% in the year 2005.

#### iv. Top 3 Sales Representatives
- Gerard Hernandez, Leslie Jennings, and Leslie Thompson are the top 3 sales representatives in terms of total sales.

#### v. Orders Counts by Season and Country
- There is a seasonal trend with higher order counts placed in the fall and spring months.
- Summer months recorded the lowest order counts.

## 3. Customer Analysis

### Charts and Insights

#### i. Top Spending Customers
- The top three spenders are Freyre Diego, followed by Nelson Susan and Ferguson Peter, all of them belonging to the high credit limit segment.

#### ii. Amount Spent vs Transactions by Credit Limit Segment
- Customers with medium credit limits did most of the transactions and spent on average approximately $100k.
- Customers with high credit limits had fewer transactions but spent more with each transaction.

#### iii. Amount Spend by Credit Limit Groups
- Customers classified in the medium credit limit spent more overall, closely followed by customers with high credit limits.

#### iv. Average Purchase vs Credit Limit by Credit Limit Segment
- Average purchase amount is directly proportional to the credit limit.
- Customers in the high credit limit segment tend to have higher average purchase amounts compared to other segments. However, the number of transactions is lower.

## 4. Product Analysis

### Charts and Insights

#### i. Top Selling Products
- The three top-selling products are the 1992 Ferrari 360 Spider red, the 1937 Lincoln Berline, and American Airlines: MD-115.

#### ii. Order Fulfilment Status
- Less than 5% of orders of classic cars, trucks, buses, and trains were delayed based on the required date and the shipped date.
- Vintage cars, Motorcycles, Planes, and ships had a 100% order fulfillment status as on time.

#### iii. Inventory Analysis
- The company has more vehicles in stock than have been ordered.
- Classic Cars are the most popular product category, with a high number of units ordered and a large inventory surplus.
- The company can consider adjusting storage for Classic Cars to reduce inventory and free up capital.

## 5. Sales Forecasting using Forecast in the Analytics panel

### Insights
- Sales are forecasted to decrease after 2005 and keep decreasing until 2007.
- The surge in gasoline prices in 2005 might have contributed to the decrease in sales.
- If gas prices decrease in the next few years, sales may increase.

## Steps taken for Creating the Dashboard

### 1. Transforming dataset

#### a. Table 1 customers
- Converting Column customerName to companyName
- Cleaning up messy phone numbers
- Converting creditLimit datatype from text to fixed decimal number ($)

#### b. Table 2 employees
- Converting officeCode datatype from text to whole number
- Identified duplicate email entries

#### c. Table 3 offices
- Converting officeCode datatype from text to whole number

#### d. Table 4 orderdetails
- Converting priceEach datatype from decimal to fixed decimal number ($)
- Converting orderLineNumber datatype from text to whole number

#### e. Table 6 payments
- Converting amount datatype from decimal to fixed decimal number ($)

#### f. Table 7 productlines
- Removed Columns htmlDescription and image

#### g. Table 8 products
- Converting quantityInStock from decimal to whole number
- Converting buyPrice and MSRP datatype from decimal to fixed decimal number ($)

### 2. Measures

- Total Customers
- Total Cost
- Total Orders
- Total Quantity
- Total customerTransactions
- Profit
- Revenue per Order

### 3. Calculated Columns

- Average Purchase Value
- creditLimitSegment
- PaymentYear
- Order Fulfillment Status
- Order Processing Time
- orderMonth
- orderSeason

**Date:**
15-02-24
