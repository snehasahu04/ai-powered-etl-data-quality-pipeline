# AI-Powered Intelligent ETL & Data Quality Monitoring Pipeline

## Overview

This project implements an end-to-end Intelligent ETL Pipeline using Azure Databricks. The solution ingests retail sales data, performs data quality validation, detects anomalies using Machine Learning, generates business insights, and visualizes results through an interactive dashboard.

## Business Problem

Retail companies receive large volumes of transaction data from multiple stores. Common challenges include:

* Duplicate records
* Missing values
* Data quality issues
* Fraudulent or anomalous transactions
* Manual investigation efforts

This project automates the entire process using Azure Databricks.

## Architecture

Raw Data → Bronze Layer → Silver Layer → ML Anomaly Detection → Gold Layer → GenAI Insights → Insight Dashboard

## Technologies Used

* Azure Databricks
* Apache Spark (PySpark)
* Delta Lake
* SQL
* Scikit-learn
* Isolation Forest
* Databricks Dashboards
* GitHub

## Features

### Bronze Layer

* Raw data ingestion
* Source data preservation

### Silver Layer

* Data cleaning
* Null value handling
* Duplicate removal
* Data type standardization
* Data quality validation

### Gold Layer

* Revenue by State
* Revenue by Product
* Revenue by Channel
* Monthly Sales Trends
* Daily Sales Trends
* Customer Purchase Analysis
* High Value Orders
* Data Quality Metrics

### Machine Learning

Implemented Isolation Forest for anomaly detection.

Generated Fields:

* anomaly_score
* is_anomaly

Purpose:

* Detect unusual transactions
* Identify potential fraud patterns

### GenAI Insights

Generated:

* Daily Pipeline Summary
* Fraud Analysis
* Data Quality Summary
* Business Insights

### Agentic AI

Implemented intelligent decision logic for:

* Fraud investigation recommendations
* Suspicious transaction review
* Pipeline health monitoring

### Dashboard

Dashboard Name: Insight Dashboard

Visualizations:

* Revenue by State
* Monthly Sales Trend
* Revenue by Channel
* State Revenue Share
* Top Products
* Customer Spending
* Daily Revenue Trend
* Average Order Value
* High Value Orders
* Anomaly Summary
* Suspicious Transactions
* Data Quality Metrics

## Project Outcomes

* Automated data quality monitoring
* ML-based anomaly detection
* Business insight generation
* Interactive analytics dashboard
* End-to-end Azure Databricks implementation

## Future Enhancements

* MLflow Model Tracking
* Azure DevOps CI/CD
* RAG-based Analytics Assistant
* Multi-Agent AI System
* Real-Time Streaming Data Processing
