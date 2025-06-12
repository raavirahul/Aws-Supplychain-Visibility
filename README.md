# Aws-Supply chain visibility
Description

Developed supply chain analytics platform to enhance inventory visibility, optimize logistics and improve demand forecasting.

Implementation

Designed a medallion archirecture(Bronze, Silve, Gold layers) for structure data processing and anlytics
Ingested real-time inventory and shipment data from IoT sensors, ERP system (SAP, Oracle) and logisitcs providers into AWS S3
Built AWS Glue ETL Pipeline to clean, Normalize, and transform data using Apache Iceberg tables for ACID complaint Upserts and time travel.
Implement a star schema using apache iceberg on Aws S3 with a medaillion architecture 
