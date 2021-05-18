# pollinate-solution
This repository is a solution for an assignment by pollinate

use draw.io to connect to github and view the below two files.

1. Refer to ERD.io for the database model design
2. Refer to Application Architecture.drawio for the business model and application high level design

Refer to the 3 PDF files for system design
1. Business Process Flow Diagram.pdf
2. Architecture Design.pdf
3. Entity Relationship Diagram.pdf


Deployment Package:

transaction_report_py_code.zip contains the python code to deploy the transaction report function in AWS lambda. Transaction report function takes the client_id as input from AWS API Gateway and returns the transactions from the transaction table.


Infrastructure as a code:

Use the transaction_report.yaml in AWS CloudFormation to deploy and manage a similar serverless application containg the API gateway and lambda function.
