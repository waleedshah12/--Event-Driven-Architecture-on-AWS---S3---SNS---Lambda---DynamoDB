⚡ Event-Driven Architecture on AWS — S3 → SNS → Lambda → DynamoDB

This project demonstrates a fully automated, serverless pipeline using AWS services to handle file uploads and store metadata in real time. It’s part of my cloud engineering portfolio, focused on building scalable, decoupled systems using event-driven design patterns.

🎯 Project Goal
Automatically capture and store metadata (filename, size, timestamp) of any file uploaded to an S3 bucket — without manual intervention or servers.
🔧 AWS Services Used
- Amazon S3: Triggers events on file uploads
- Amazon SNS: Publishes notifications to subscribed Lambda
- AWS Lambda: Extracts file metadata and formats it
- Amazon DynamoDB: Stores metadata in a scalable NoSQL table
- Amazon CloudWatch: Monitors logs and system health
- 
✅ Key Learnings
- Designing event-driven, decoupled architectures
- Configuring IAM roles for secure service communication
- Debugging with CloudWatch Logs
- Building serverless automation pipelines with zero infrastructure management
- 
📎 Project Assets
- Architecture diagram
- Lambda function code
- IAM policy snippets
- Sample metadata entries in DynamoDB
- 
🚀 What’s Next
I’ll be integrating CloudWatch alarms and SNS email alerts to notify me of any failures in the pipeline — adding observability for production readiness.
