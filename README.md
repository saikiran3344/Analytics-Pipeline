# Customer Behavior Analytics Pipeline

This project contains a Lambda function for processing and storing customer interaction logs in AWS S3 for downstream analytics.

## How to Run
1. Deploy the `lambda_function.py` code to AWS Lambda.
2. Configure AWS permissions to allow access to the S3 bucket (`customer-interactions`).
3. Trigger the function by integrating with a message queue or direct invocation.

## Purpose
This pipeline captures real-time customer data, which is then used for behavioral analytics and customer insights.
