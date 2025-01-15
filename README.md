# Automated ETL Pipeline for E-commerce Data

## Overview
This project automates the process of Extracting, Transforming, and Loading (ETL) product data from CSV files into a Snowflake database using Apache Airflow. The pipeline ensures efficient handling of large datasets, automating the flow of data through scheduled and monitored processes, with retries for error handling.

## Architecture
![ETL Flow Diagram](Automate-etl-pipeline.jpg)

## Technologies used
- **Programming Language** : Python
- **Data Processing** : Pandas
- **Workflow Orchestration** : Apache Airflow
- **Database** : Snowflake
- **File Handling** : CSV files

## Features:
Automated ETL Process: Designed a robust automated ETL pipeline using Apache Airflow that handles the full process from file extraction to loading in the Snowflake database.

Data Extraction: Efficiently extracts product data from CSV files, handling large datasets seamlessly with built-in error handling to ensure smooth execution.

Data Transformation: Data cleaning, formatting, and normalization using Pandas to ensure that the data is properly structured for loading into Snowflake.

Snowflake Integration: Successfully integrates and loads transformed data into a Snowflake database, ensuring scalability and high performance with cloud data warehousing.

Orchestration with Airflow: Airflow DAGs automate the ETL flow, managing task scheduling, logging, and retry mechanisms, ensuring proper task execution and reliability.

## Dataset Used
https://www.kaggle.com/datasets/ahmedsayed564/amazon-sales-dataset

## Conclusion
The ETL pipeline automation project efficiently extracts, transforms, and loads large datasets from CSV files into Snowflake using Apache Airflow. By integrating Python, Pandas, and Snowflake, the pipeline ensures high performance, scalability, and reliability. Airflow automates scheduling, monitoring, and error handling, making the process seamless. This project demonstrates an effective solution for managing large-scale data efficiently, reducing manual intervention, and ensuring data readiness for analytics.
