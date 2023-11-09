WILDRIDES WEBSITE

List of Used Services:

1.Code Commit
2.Amplify
3.Cognito
4.Lambda
5.API Gateway
6.DynamoDB

Requirements:

AWS Account with Consol Acess
ArcGIS Free Account

STEPS:

1.Empty Repo in CodeCommit with required IAM Permissions and Git Credientials 
2.Clone the repo in empty folder
3.Copy the Contents from web folder or from S3 //aws s3 cp s3://wildrydes-[your_region_name, like us-west-2]/WebApplication/1_StaticWebHosting/website ./ --recursive
4.Push the contents to the repo (git add, commit, push)
5.Create new web app with Amplify with CodeCommit with Auto Deploy
6.Create User Pool using Cognito 
7.Update the Congif file in the web app
8.Create a DB using DynamoDB
9.Impleminting the Ride Share with Lambda with test cases.
10.REST API Integritation with API Gateway
11.Update the Ride.html
12.Test the Application 

DELETE THE RESOURCES



***
Code originally included in the Amazon Wild Rydes workshop: https://aws.amazon.com/getting-started/hands-on/build-serverless-web-app-lambda-apigateway-s3-dynamodb-cognito/module-3/ 
***
