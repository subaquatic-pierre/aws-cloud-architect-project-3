# AWS Cloud Architect - Project 3

Build a DevSecOps pipeline

## Enable AWS Security Services

1. Enable AWS Config
2. Enable AWS Security HUB
3. Enable AWS Inspector scan

   - Enable scan, click default
   - Progress to Advanced setup
   - Select tags to assign inspector agent

4. Enable AWS Guard Duty

AWS Cloud Architect course - Project 3 - Udacity

## Resources

### Web App

#### Load Balancer Endpoint

- c1-web-service-alb-1771411232.us-east-1.elb.amazonaws.com

#### App Instance IP

- ec2-54-204-178-23.compute-1.amazonaws.com

#### Attack Instance IP

- ec2-52-90-237-133.compute-1.amazonaws.com

### S3

#### Bucket Names

- BucketArnVPCFlowLogs
  - ARN: arn:aws:s3:::cand-c3-vpc-flow-logs-032796414879
- BucketNameRecipesFree
  - ARN: arn:aws:s3:::cand-c3-free-recipes-032796414879
- BucketNameRecipesSecret
  - ARN: arn:aws:s3:::cand-c3-secret-recipes-032796414879
