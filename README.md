# aws-portfolio-website-s3-cloudfront
live AWS portfolio website hosted on S3= cloudfront with https, OAI security,and cache invalidation.Build for cloud operations engineer role.
# AWS Portfolio Website - S3 + CloudFront

**Live URL:** https://d2una8110j1geb.cloudfront.net

## About This Project
Deployed a professional portfolio website using AWS services. Focused on scalability, security, and cost optimization.

## AWS Services Used
- **S3:** Static website hosting
- **CloudFront:** Global CDN + HTTPS + Caching
- **OAI (Origin Access Identity):** Secure S3 access, bucket not public
- **ACM:** SSL/TLS Certificate for HTTPS
- **IAM:** Least privilege access for deployment

## Key Implementations
1.  **High Availability:** CloudFront edge locations for low latency globally
2.  **Security:** S3 bucket private, accessed only via CloudFront OAI
3.  **Cost Optimization:** WAF disabled for static site, Price Class 100 used
4.  **DevOps Practice:** Cache invalidation performed for content updates

## Screenshots
Check the `/screenshots` folder for proof of implementation:
1. Live website with HTTPS
2. S3 bucket configuration 
3. CloudFront distribution setup
4. OAI security configuration
5. Cache invalidation workflow

## Skills Demonstrated
EC2, ASG, ALB, S3, CloudFront, CloudWatch, IAM, VPC, Cost Optimization, Troubleshooting

---
**Built by:** Sona Rasal | Aspiring AWS Cloud Operations Engineer
