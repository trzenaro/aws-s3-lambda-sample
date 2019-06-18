## Setup
Go to AWS Console → IAM → Users
Add a user "**serverless-node**" and add the "**AdministratorAccess**" permission

Install serverless lib:
`npm install -g serverless`

Setting up your AWS user
`serverless config credentials -o --provider aws --key=<USER_KEY> --secret=<USER_SECRET>`

## Deploy your project
`npm run deploy`