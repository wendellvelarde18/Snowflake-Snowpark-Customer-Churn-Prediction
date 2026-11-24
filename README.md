# Customer Churn Prediction with Snowflake Snowpark Python

## Overview
An end-to-end machine learning learning project using Snowflake Snowpark Python, pandas, and scikit-learn.

Based on the Snowflake-Labs Getting Started with Snowpark Python Quickstart, with adaptations for role-based access, safe data handling, model training, and UDF deployment.

## Results
- Raw dataset: 100,000 records
- Training dataset: 20,000 records
- Algorithm: Random Forest
- Test balanced accuracy: 97.78%
- Deployment: Snowflake Python UDF
- Prediction validation: 400 records
- Prediction sample accuracy: 98.50%

The 400-row prediction validation used training-table data and is not an independent holdout result.

## Workflow
1. Data ingestion and feature engineering with Snowpark
2. Exploratory data analysis and preprocessing
3. Random Forest training and evaluation
4. In-database prediction using a Snowflake Python UDF

## Security
Credentials, customer data, and environment-specific identifiers are excluded from the public portfolio.

## Attribution
Adapted from the Snowflake-Labs Getting Started with Snowpark Python Quickstart:
https://github.com/Snowflake-Labs/sfguide-getting-started-snowpark-python

## Publication Note
Notebook redistribution is pending confirmation of the upstream project's license.
