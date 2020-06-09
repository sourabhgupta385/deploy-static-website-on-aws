# Deploy Static Website on AWS
This is one of the project in Udacity Cloud DevOps Engineer Nanodegree.

## Project Overview

In this project, you will deploy a static website to AWS using S3, CloudFront, and IAM.

## Project Files

- `index.html` - The Index document for the website.
- `/img` - The background image file for the website.
- `/vendor` - Bootssrap CSS framework, Font, and JavaScript libraries needed for the website to function.
- `/css` - CSS files for the website.

## Project Setup

Below is the overall process. You can access the `screenshots` folder to have better understanding:

- Create a S3 bucket
- Upload the website files to your bucket
- Configure the bucket for website hosting
- Secure the bucket using IAM policies
- Speed up content delivery using AWS’ content distribution network service, CloudFront
- Access your website in a browser using the unique CloudFront endpoint