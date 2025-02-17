# YouTube-Data-Analysis-End-to-End-Data-Engineering-Project

## Project Overview  
This is an **end-to-end Data Engineering project** where I implemented a **YouTube Trending Videos Analysis Pipeline** using AWS services. The goal of this project is to **extract, clean, process, and analyze YouTube trending videos** to understand factors that influence video popularity.  

This project was originally created by **Darshil Parmar**, and I executed it step by step to learn and gain hands-on experience in **AWS-based data pipelines**.  

## Technologies Used  
- **Programming:** Python  
- **Cloud Services:** AWS (S3, Glue, Lambda, Athena, IAM)  
- **Data Processing:** Pandas, AWS Wrangler  
- **Storage Formats:** JSON, Parquet  
- **Querying:** SQL (Athena)  

## Project Workflow  
**Data Collection**  
   - Downloaded **YouTube Trending Videos Dataset** from Kaggle.  
   - Stored raw data in **Amazon S3**.  

**Data Cleaning & Processing**  
   - Used **AWS Lambda** to clean JSON data and convert it to **Parquet format** for better performance.  

**Data Cataloging**  
   - Created a **Glue Crawler & Data Catalog** to organize metadata.  

**Querying & Analysis**  
   - Ran **SQL queries in AWS Athena** to extract insights.  

**ETL Automation**  
   - Built an **AWS Glue ETL Job** to transform raw CSV data into structured format.  

**Partitioning & Optimization**  
   - Partitioned data **by region** to improve query efficiency.  

## 🔹 AWS Services Used  
- **Amazon S3** – Stores raw and processed data.  
- **AWS Glue** – Automates ETL and builds a data catalog.  
- **AWS Lambda** – Transforms raw data into a structured format.  
- **AWS Athena** – Runs SQL queries directly on S3 data.  
- **AWS IAM** – Manages permissions securely.  
