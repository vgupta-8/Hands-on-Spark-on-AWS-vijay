# Serverless Spark ETL Pipeline on AWS

## Architecture
S3 Landing Bucket → Lambda Trigger → AWS Glue ETL Job → Processed S3 Output

## AWS Services Used
- Amazon S3
- AWS Lambda
- AWS Glue
- Apache Spark

## Implementation Steps
1. Created S3 landing and processed buckets.
2. Uploaded reviews.csv to landing bucket.
3. Created AWS Glue ETL job and executed Spark transformations.
4. Created Lambda function to trigger Glue job.
5. Configured S3 event trigger.
6. Verified output generated in processed-data and Athena Results folders.

## Results
Glue job executed successfully and generated analytics outputs in S3.
