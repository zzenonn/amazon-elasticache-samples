# Amazon ElastiCache for Redis

**Boosting database performance with Amazon ElastiCache for Redis**

[Deploy the CloudFormation template elc-demo-env.yaml](https://ap-southeast-1.console.aws.amazon.com/cloudformation/home?region=ap-southeast-1#/stacks/quickcreate?templateUrl=https%3A%2F%2Fs3-ap-southeast-1.amazonaws.com%2Fcf-templates-1jeq0zdbrc01p-ap-southeast-1%2F2020293bCK-elc-demo-env.yaml&stackName=Demo&param_DBUsername=zenon&param_SecurityGroup=sg-029c4d679932a9df7&param_SubnetGroup%5B%5D=subnet-01d5c7838b48edd16&param_SubnetGroup%5B%5D=subnet-0ebec9e9da7819503&param_VPC=vpc-03985b17aae1b37c7)

Export the following environment variables

```bash
export REDIS_URL=redis://<redis endpoint>:6379/
export DB_HOST=<dbHost>
export DB_USER=zenon
export DB_PASS=Password1
export DB_NAME=tutorial
```