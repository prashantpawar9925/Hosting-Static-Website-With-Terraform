## Project: Hosting Static Website on AWS using S3, CloudFront with Terraform.

# Problem Statement :

The website stores and serves a significant amount of static content from an Amazon S3 bucket. Users are located across India, 
and due to geographical distance from the S3 bucket’s region (presumably in a distant AWS region like ap-south-1 ), 
users experience higher latency and slower load times. This impacts user satisfaction.


# Solution :

To Implement Amazon CloudFront to deliver content with low latency and improved performance for users accessing the website from various locations across India.

1) S3 Bucket : To Store Static Content

2) CloudFront: To deliver content with low latency and improved performance.

3) Route53 (Optional) : To use for Domain Management 
