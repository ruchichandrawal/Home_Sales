# Home_Sales

# Summary: Home Sales Data Analysis with SparkSQL

This assignment revolves around utilizing the power of Apache Spark and SparkSQL to conduct a comprehensive analysis of home sales data. The primary objectives include deriving key metrics from the dataset, creating temporary views, optimizing data storage, and understanding the caching mechanisms within Spark.

## Assignment Setup

1. **Repository Creation**: A dedicated GitHub repository named "Home_Sales" was established to house the assignment.

2. **Local Setup**: The repository was cloned to the local machine for collaborative development.

3. **File Acquisition**: Essential assignment files were obtained from the provided link.

## Analysis Workflow

1. **Notebook Creation**: The `Home_Sales_starter_code.ipynb` file was renamed as `Home_Sales.ipynb`, serving as the platform for the entire analysis.

2. **Dependencies**: Necessary PySpark SQL functions were imported to facilitate SparkSQL operations.

3. **Data Ingestion**: The `home_sales_revised.csv` data was read into a Spark DataFrame to lay the groundwork for analysis.

4. **Temporary Table Creation**: A temporary table named "home_sales" was established from the DataFrame, enabling SparkSQL queries.

5. **Metric Calculation**: Using SparkSQL, a series of questions were answered by calculating average prices, view ratings, and other key metrics.

6. **Caching**: The performance of queries was enhanced by caching the "home_sales" temporary table, improving data access speeds.

7. **Caching Verification**: The caching process was confirmed to ensure the temporary table was cached effectively.

8. **Cached Query**: A query utilizing the cached data filtered view ratings for high-priced homes. Query runtime was compared against uncached runtime.

9. **Data Partitioning**: Optimizing data storage was achieved by partitioning the home sales data based on the "date_built" field.

10. **Parquet Table**: A temporary table for the partitioned parquet home sales data was established, primed for further analysis.

11. **Parquet Query**: A query on the parquet data identified view ratings for high-priced homes. Query runtime was compared against uncached runtime.

12. **Uncaching**: Memory resources were freed by uncaching the "home_sales" temporary table.

13. **Verification**: Successful uncaching of the "home_sales" table was verified using PySpark.


This assignment not only showcased the capabilities of SparkSQL in handling and analyzing data but also highlighted the importance of effective collaboration and resource utilization.
