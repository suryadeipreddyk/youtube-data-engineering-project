# YouTube Data Engineering Project

### Project Overview
----
This project is designed to build a scalable **data engineering pipeline** for processing and analyzing YouTube data using **AWS services**. The pipeline ingests raw data from YouTube, transforms it into a structured format, and stores it for analytics and reporting. The final processed data is used for business intelligence and visualization.


For a detailed breakdown of the project, visit the <a href="https://devengine.notion.site/YouTube-Data-Engineering-Project-18e32fa5808880579491ce5e5f96e8d6?pvs=74" target="_blank">YouTube Data Engineering Documentation</a>.

**Dataset:** https://www.kaggle.com/datasets/datasnaek/youtube-new


### Architecture Overview
---
The AWS-based data architecture enables efficient data ingestion, processing, and storage. Here’s how it works:
1. **Data Ingestion**: Data is ingested from source systems via the **S3 API** into an **S3 Landing Area**.
2. **Data Transformation**: **AWS Glue** and **AWS Lambda** handle data cleansing, enrichment, and transformation. **AWS Step Functions** orchestrate workflows.
3. **Data Storage**: Processed data is stored in **S3** and cataloged in the **AWS Glue Data Catalog** for querying via **AWS Athena**.
4. **Security & Monitoring**: Security is managed with **IAM**, and monitoring is done via **CloudWatch**.
5. **Analytics & Visualization**: The final data is used for analysis using **QuickSight, Power BI, and Qlik**.
![Alt Text](https://github.com/suryadeipreddyk/youtube-data-engineering-project/blob/main/Youtube%20Data%20Engineering%20Architecture.png)


### Tools & Technologies
---
- **AWS Services**: S3, Glue, Lambda, Step Functions, Athena, IAM, CloudWatch
- **Data Formats**: JSON, CSV, Parquet
- **Programming**: Python (for Lambda functions and Glue ETL scripts)
- **Visualization**: QuickSight, Power BI, Qlik


---

For a detailed breakdown of the project, visit the [YouTube Data Engineering Documentation](https://devengine.notion.site/YouTube-Data-Engineering-Project-18e32fa5808880579491ce5e5f96e8d6?pvs=74).
