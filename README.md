# Data Engineering project on youtube video statistics

## Overview
In this project, I worked on organizing, simplifying, and analyzing data from YouTube videos, focusing on different video categories and their popularity metrics.

## Project Goals
* Data Ingestion — I set up a system to collect data from various sources.
* ETL System — I transformed the raw data into a structured format suitable for analysis.
* Data Lake — I created a central storage space on the cloud to keep data coming from multiple sources.
* Scalability — I ensured that our system could handle increasing amounts of data without performance loss.
* Cloud Usage — To manage large data volumes, I utilized cloud services, specifically AWS, for processing and storage.
* Reporting — I developed a dashboard to visualize and interpret the data, helping answer specific analytical questions.
## Services Used
* Amazon S3: Used for scalable and secure object storage of data.
* AWS IAM: Managed secure access to AWS services and resources.
* QuickSight: Employed for creating scalable and interactive dashboards powered by machine learning.
* AWS Glue: Used for data integration tasks, making it easier to prepare and combine data for analysis.
* AWS Lambda: Allowed me to run code in response to events without managing servers.
* AWS Athena: Used for running interactive queries directly on data stored in S3.
## Dataset Used
The dataset, sourced from Kaggle, includes daily statistics of popular YouTube videos, such as video titles, channel details, publication times, tags, views, likes, dislikes, descriptions, and comments. Each region's data is stored separately, with unique identifiers for video categories in the associated JSON files.
 --  https://www.kaggle.com/datasets/datasnaek/youtube-new
