# Rajiv Unnikrishnan

## AWS engineering, Bedrock agents and retrieval-augmented generation

I build AI assistants around business data and work on the AWS infrastructure and API integrations behind them. Based in Amsterdam, Netherlands.

My focus is Python, Amazon Bedrock, Lambda, API Gateway, S3, DynamoDB, Athena, and document retrieval with PostgreSQL/pgvector. I also work with Amazon Connect, Lex, QuickSight and Redshift.

### Selected projects

| Project | What to look at | Stack |
| --- | --- | --- |
| [Document retrieval API](https://github.com/rajivunni/rag-document-retrieval) | Google Drive ingestion, text extraction, chunking, embeddings and source retrieval, with mocked unit tests | Python, FastAPI, OpenAI embeddings, Supabase, pgvector |
| [AWS subscription lifecycle reference](https://github.com/rajivunni/aws-serverless-subscription-provisioning) | Anonymized subscription lifecycle reference with webhook validation and workflow orchestration | Go, Lambda, DynamoDB, Step Functions, API Gateway |
| [AWS operational health checks](https://github.com/rajivunni/aws-serverless-health-check) | Read-only AWS operational checks with mocked offline tests | Python, AWS CLI, CloudWatch, DynamoDB, SNS |
| [AWS service cost report](https://github.com/rajivunni/aws-bedrock-cost-report) | Selected-service Cost Explorer reporting to Excel and JSON, with a synthetic offline demo | Python, AWS Cost Explorer, openpyxl |
| [Amazon Connect healthcare POC](https://github.com/rajivunni/connect-healthcare-poc) | Contact-center infrastructure and intent handling using fictional healthcare records | Amazon Connect, Lex V2, Lambda, CloudFormation |
| [FreshBite analytics POC](https://github.com/rajivunni/freshbite-quicksight-poc) | Synthetic franchise data, warehouse SQL and a QuickSight permissions-table design | Redshift Serverless, QuickSight, S3, CloudFormation, Python |

### AWS + RAG demonstration

[MedCare assistant](https://d3koirx16s0e80.cloudfront.net/) is a portfolio POC using synthetic healthcare data. It combines document Q&A with source citations and structured reporting through a React interface, API Gateway, Python Lambda, Amazon Bedrock and Athena. It is a demonstration, not a production healthcare system or a compliance certification.

### How I work

I start with the data path and the actual failure or user question. I prefer small, testable changes, clear source evidence and written setup notes. My client work includes AWS integration recovery, Bedrock operations agents and Terraform pre-deployment reviews. Original client repositories and production data remain private; anonymized portfolio adaptations are labelled separately.

These public repositories are demos and anonymized portfolio adaptations. Each README describes what the code implements, what is mocked and what still needs work before a production deployment. The subscription lifecycle repository is reference code, not a production-ready deployment package.

[Website](https://flowboticsai.com/) · [GitHub](https://github.com/rajivunni)
