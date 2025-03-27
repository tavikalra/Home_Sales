# Home_Sales

This repository contains a Jupyter Notebook (`Home_Sales.ipynb`) that uses PySpark to analyze home sales data.  The notebook performs several tasks, including:

1.  Reading data from an AWS S3 bucket.
2.  Creating temporary views and tables in Spark.
3.  Executing SparkSQL queries to answer specific questions about the data.
4.  Caching and uncaching Spark tables.
5.  Partitioning data using Parquet format.
6. Comparing query runtimes for cached, uncached, and partitioned data.

The project demonstrates practical applications of Spark for data manipulation, analysis, and performance optimization. A detailed explanation of the code is available in `Home_Sales_ipynb_Explanation.pdf`.