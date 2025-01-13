# Home_Sales
In this challenge, you'll apply SparkSQL to analyze home sales data. You'll use Spark to create temporary views, partition data, and manage caching for a temporary table.

## **SparkSQL Queries:**
1. Find the average price of four-bedroom houses sold each year (rounded to 2 decimals).
2. Find the average price of homes with 3 bedrooms and 3 bathrooms, by year built (rounded to 2 decimals).
3. Find the average price of homes with 3 bedrooms, 3 bathrooms, 2 floors, and at least 2,000 sq. ft., by year built (rounded to 2 decimals).
4. Find the average price of homes per "view" rating where the price is ≥ $350,000. Track the query runtime.

## **Data Management:**
1. Cache the `home_sales` table and check if it's cached.
2. Run the last query on the cached data and compare runtime with the uncached version.
3. Partition the data by the `date_built` field and store it in Parquet format.
4. Create a temporary table from the Parquet data.
5. Run the query on the Parquet data and compare the runtime with uncached data.
6. Uncache the `home_sales` table and verify it's uncached.
