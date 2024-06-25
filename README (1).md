## Functionality

The code performs various analyses on the sales data, including:

## About Data
The dataset was obtained from the Kaggle Walmart Sales Forecasting Competition. This dataset contains sales transactions from a three different branches of Walmart, respectively located in Mandalay, Yangon and Naypyitaw. The data contains 17 columns and 1000 rows:

 
## Data Exploration:

Identifies the unique values in specific columns (city, product line, customer type, payment method).
Calculates basic statistics like average sales quantity, average rating, etc.

## Sales Analysis:

Analyzes sales performance by factors like time of day, day of week, product line, customer type, and branch.
Calculates total revenue by month.
Identifies the product lines with the highest revenue and VAT.
Compares sales performance across different branches and customer types.

## Customer Analysis:

Identifies the most common customer types and payment methods.
Analyzes customer behavior based on gender and purchase time.

## Code Structure
The code consists of several SQL queries that achieve specific analysis tasks.

## Initial Queries:

Selects all data from the sales table.
Creates new columns for time_of_day, day_name, and month_name derived from existing columns.

## Analysis Queries:

Analyzes sales data by various factors like city, branch, product line, month, etc.
Calculates metrics like total revenue, average ratings, VAT per customer type, etc.
Uses conditional logic to categorize product lines based on average sales.

## Usage

Clone this repository to your local machine.
Ensure you have access to a MySQL database containing the sales table with the required columns.
Connect your SQL client to the MySQL database.
Execute the SQL queries provided in the code (or a combination of them depending on your desired analysis).
The queries will return results based on your specific data, providing insights into sales trends, customer behavior, and performance across different categories.

## Contributing

Feel free to contribute to this project by forking the repository and submitting pull requests with additional analysis queries or improvements to the existing code.

## Generic Question

How many unique cities does the data have?
In which city is each branch?

## Product

How many unique product lines does the data have?
What is the most common payment method?
What is the most selling product line?
What is the total revenue by month?
What month had the largest COGS?
What product line had the largest revenue?
What is the city with the largest revenue?
What product line had the largest VAT?
Fetch each product line and add a column to those product line showing "Good", "Bad". Good if its greater than average sales
Which branch sold more products than average product sold?
What is the most common product line by gender?
What is the average rating of each product line?

## Sales

Number of sales made in each time of the day per weekday
Which of the customer types brings the most revenue?
Which city has the largest tax percent/ VAT (Value Added Tax)?
Which customer type pays the most in VAT?

## Customer

How many unique customer types does the data have?
How many unique payment methods does the data have?
What is the most common customer type?
Which customer type buys the most?
What is the gender of most of the customers?
What is the gender distribution per branch?
Which time of the day do customers give most ratings?
Which time of the day do customers give most ratings per branch?
Which day fo the week has the best avg ratings?
Which day of the week has the best average ratings per branch?
