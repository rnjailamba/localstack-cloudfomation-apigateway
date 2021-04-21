# localstack-cloudformation-lambda-eventbridge

System information
1. `aws --version`
`aws-cli/1.19.53 Python/3.8.2 Darwin/19.4.0 botocore/1.20.54`
2. `awslocal --version`
`aws-cli/1.19.53 Python/3.8.2 Darwin/19.4.0 botocore/1.20.54`

Steps to reproduce the issue
1. `docker-compose --env-file .env up -d` with the .env file only consisting of the API Key
2. Run `sh ./1-cloudformation-deploy.sh` to create cloudformation stack and deploy locally
