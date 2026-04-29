# Big Data Systems & Stock Forecasting Dashboard

This project combines big data storage, database benchmarking, real-time analytics, and predictive modelling into an end-to-end data pipeline.

The project explores how large-scale data systems can support practical analytics by integrating Hadoop, Hive, MongoDB, Redis, MySQL, Spark, machine learning models, stock price data, and Twitter sentiment data.

## Project Overview

The aim of this project was to design, implement, and evaluate a big data analytics workflow from storage through to insight delivery.

The project includes:

- Distributed data storage and querying using Hadoop and Hive
- NoSQL data handling using MongoDB
- Database benchmarking using YCSB
- Comparative analysis of Redis, MongoDB, and MySQL
- Real-time analytics architecture using Spark
- Predictive modelling using stock prices and tweet sentiment
- Interactive Streamlit dashboard for forecast exploration

This project demonstrates both data engineering and advanced analytics skills.

## Key Features

- Implemented Hadoop-based storage and Hive querying
- Stored and queried data in MongoDB
- Compared Redis, MongoDB, and MySQL using YCSB workloads
- Designed a big data system architecture
- Implemented Spark-based real-time analytics
- Built stock forecasting models using financial and sentiment data
- Created an interactive Streamlit dashboard for model comparison
- Evaluated forecasts across companies, models, and time horizons

## Technologies Used

- Python
- Jupyter Notebook
- Hadoop
- Hive
- MongoDB
- Redis
- MySQL
- Apache Spark
- YCSB
- Streamlit
- Plotly
- Pandas
- Machine Learning / Time Series Models

## Big Data Storage & Processing

The project uses Hadoop for distributed storage and Hive for querying large datasets. MongoDB was used for document-based storage and operations, demonstrating how different storage systems can support different types of data access and processing needs.

This reflects a realistic big data environment where structured, semi-structured, and flexible storage systems may all be used within the same pipeline.

## Database Benchmarking with YCSB

A major part of the project involved benchmarking Redis, MongoDB, and MySQL using the Yahoo Cloud Serving Benchmark (YCSB).

Workloads A, B, and C were used to compare database performance under different read/write patterns.

The benchmarking showed that database choice depends heavily on workload type. No single database is best for every scenario, so system design should be based on access patterns, latency requirements, and scalability needs.

## Real-Time Analytics

The project includes a real-time analytics architecture using Apache Spark.

Spark was used to demonstrate how a big data system can support faster processing and near real-time insight generation. This part of the project focuses on how batch-style data storage can be extended into real-time analytics workflows.

## Stock Forecasting & Sentiment Analysis

The advanced analytics section combines stock price data with Twitter sentiment data to forecast stock movements.

Forecasts were created for:

- Apple
- Amazon
- Tesla
- Microsoft
- Boeing

Models included:

- LSTM
- ARIMA
- ARIMAX
- XGBoost

Forecast horizons included:

- 1-day forecasts
- 3-day forecasts
- 7-day forecasts

This allowed comparison of different modelling approaches across multiple companies and prediction windows.

## Dashboard

The project includes an interactive Streamlit dashboard for exploring stock forecasts and sentiment trends.

Users can:

- Select a company ticker
- Compare actual stock prices against model forecasts
- Toggle forecast models on and off
- View sentiment trends over time
- Filter RMSE scores by ticker, model, and forecast horizon

The dashboard uses Plotly visualisations to make model performance easier to understand and compare.

## Key Insights

- Database performance varies significantly depending on workload type
- Redis, MongoDB, and MySQL each have strengths depending on access patterns
- Distributed storage improves scalability but adds system complexity
- Real-time analytics requires careful architecture planning
- Combining stock prices with sentiment data can improve the richness of forecasting analysis
- Forecast performance varies by company, model, and prediction horizon

## Limitations

- Benchmarking was limited by available local infrastructure
- Real-time analytics was implemented at a project scale rather than production scale
- Forecasting results depend on the quality and coverage of stock and sentiment data
- Larger datasets and cloud deployment would allow deeper scalability testing

## What I Demonstrated

This project demonstrates my ability to:

- Design and implement big data storage workflows
- Work with Hadoop, Hive, MongoDB, Redis, MySQL, and Spark
- Benchmark database systems using YCSB
- Compare database performance across different workloads
- Build real-time analytics architecture
- Combine structured financial data with unstructured sentiment data
- Develop machine learning and time series forecasting models
- Create an interactive dashboard for communicating results
- Explain system trade-offs clearly and practically
