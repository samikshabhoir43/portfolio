# Portfolio Website - CI/CD Deployment

## 📌 Project Overview

A static portfolio website deployed automatically to AWS S3 using
GitLab CI/CD.
- first create s3 bucket ->public access enable 
- github actions code
- 
## 🛠️ Technologies

- HTML
- CSS
- JavaScript
- Git
- GitLab CI/CD
- AWS S3
- AWS IAM
- Linux

## 🔄 CI/CD Pipeline

Developer
↓
GitLab
↓
GitLab CI/CD
↓
AWS S3
↓
Live Website

## ⚙️ Features

- Automated deployment
- AWS S3 hosting
- GitLab CI/CD pipeline
- IAM-based AWS authentication
- Automatic synchronization of website files

## AWS s3 permission bucket policy 

{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Sid": "PublicReadGetObject",
            "Effect": "Allow",
            "Principal": "*",
            "Action": "s3:GetObject",
            "Resource": "arn:aws:s3:::portfoliosamiksha/*"
        }
    ]
}


