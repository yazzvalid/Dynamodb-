# DynamoDB Local Table Manager

A Python script to create and interact with a DynamoDB table locally using `boto3`.

## Features
- Creates a local DynamoDB table named `Transactions`
- Inserts sample transaction data
- Scans and displays all table items

## Prerequisites
- Python 3.x
- boto3 (`pip install boto3`)
- DynamoDB Local (Download from [AWS](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/DynamoDBLocal.DownloadingAndRunning.html))

## Usage
1. Start DynamoDB Local:
   ```bash
   java -Djava.library.path=./DynamoDBLocal_lib -jar DynamoDBLocal.jar -sharedDb
