# Data Engineering pipeline for NYC Taxis dataset using Azure Synapse analytics

NYC Taxis data is imported into the bronze layer manually to explore different datatypes apart from CSV. Serverless SQL pool is used for compute purposes. Before ingestion data discovery is performed where OPENROWSET function is explored. The data is then ingested into the silver layer and further transformed into the gold layer. In all these phases external tables and views are created for querying through T-SQL. Power BI is then used to report on top of the gold layer by connecting to the serverless SQL pool. Scheduling and monitoring practices are followed and exploration of other azure solutions to the problem.

![image](https://github.com/srikrishna777k/Data-Engineering-pipeline-using-Azure-Synapse-analytics/assets/75556669/b9c4be0b-1d61-4cef-89b0-a9ce62d0d210)


