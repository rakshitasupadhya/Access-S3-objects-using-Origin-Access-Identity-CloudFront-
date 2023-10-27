# Access-S3-objects-using-Origin-Access-Identity-CloudFront-
This is simple demonstration on accessing S3 objects using only OAI in CloudFront

# Architecture
![image](https://github.com/rakshitasupadhya/Access-S3-objects-using-Origin-Access-Identity-CloudFront-/assets/107621546/16996a31-c938-4cc4-8ef3-ab1086269d00)

# Implementation
1. Create a S3 bucket and enable public access and upload image to the bucket
2. Access the image through S3- image should be displayed successfully
3. Create a CloudFront distribution – Create an Origin Access Identity
4. Complete distribution configuration by allowing read access to CloudFront origin access control in your policy statement
5. Once the distribution is ready check if image can be accessed using CloudFront
6. Restrict Access – Remove public read access from bucket. This will allow users to access the image using only CloudFront  URL.
