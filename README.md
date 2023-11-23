# Real-Time Stock Market Data Ingestion Pipeline

## Introduction 
This project sets up an end-to-end Real-Time Stock Market Data Ingestion pipeline using Apache Kafka, AWS EC2, S3, Glue, and Athena. 
The pipeline includes steps for launching an EC2 instance, installing and configuring necessary packages, creating Kafka topics, 
producing and consuming real-time data, and querying the data using AWS Athena.

## Architecture 
<img src="Architecture.png">

## Technology Used
- Programming Language - Python
- Amazon Web Service (AWS)
1. S3 (Simple Storage Service)
2. Athena
3. Glue Crawler
4. Glue Catalog
5. EC2
- Apache Kafka


## Dataset Used

Here is the dataset used in the project - https://github.com/rita2002-max/stock-market-kafka-data-engineering-project/blob/main/indexProcessed.csv

## Getting Started

### Step 1: Launching an EC2 Instance
Launch an EC2 instance with default properties.
Add a Security Group allowing traffic from All IPs for internet access.

### Step 2: Logging in to the Instance using SSH
Download the primary key and move it to the project folder.
SSH into the instance using the provided command in the Connect section.

### Step 3: Installing and Downloading Required Packages


