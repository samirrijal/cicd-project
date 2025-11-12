# Project 01 - AWS CI/CD Pipeline 🚀

This is my first DevOps project where I built a CI/CD pipeline on AWS to automate the deployment of a Vite-based web app. The pipeline connects GitHub to AWS services, ensuring that every code push automatically builds and deploys the latest version of the project.

## 🧰 Tech Stack
- AWS CodePipeline  
- AWS CodeBuild  
- AWS S3  
- AWS IAM  
- Vite  

## ⚙️ How It Works
1. Code is pushed to the GitHub repository.  
2. AWS CodePipeline detects the change and starts the pipeline.  
3. CodeBuild runs the Vite build process and generates the production-ready files.  
4. The output files are automatically deployed to an S3 bucket for hosting.  

## 🔐 IAM Setup
An IAM user was configured with appropriate roles and permissions to handle CodePipeline, CodeBuild, and S3 access securely. This ensures safe and reliable automation with minimal manual involvement.

## 💡 What I Learned
- How to design a basic CI/CD pipeline using AWS tools  
- Connecting GitHub to AWS CodePipeline for automated workflows  
- Managing IAM users, roles, and policies effectively  
- Understanding the flow of continuous integration and deployment in a real environment  

## 📂 Project Structure
samirrijal/
├── index.html
├── styles.css
├── script.js
├── shaders.js
├── package.json
├── package-lock.json
├── .gitignore
└── .DS_Store

## 🚀 Result
Every push to the main branch in GitHub automatically triggers the pipeline, builds the app using Vite, and deploys the updated version to the S3 bucket. This marks the beginning of my DevOps journey and my first step into continuous deployment automation.