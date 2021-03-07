# Lambda template

### Use this template to create a new service

```
serverless create --template-path ./template --path user-service
```

### Create a lambda function

```
serverless create function -f createUser --handler src/functions/createUser.createUser --path src/tests
```

### Run unit tests

```
npx mocha src/tests
```

### Command to create a brand new service

Use this if you dont want to use the template for whatever reason

```
serverless create --template aws-nodejs
```
