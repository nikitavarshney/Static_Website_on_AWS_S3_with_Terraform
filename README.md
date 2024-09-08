# Static Website on AWS S3 with Terraform

This project demonstrates how to deploy a static website(Portfolio) using AWS S3 and Terraform. The infrastructure is defined as code using Terraform, allowing for easy provisioning and management of AWS resources.

## Project Overview

This repository contains the code and configuration files to host a static website on an AWS S3 bucket. Terraform is used to automate the creation of the S3 bucket, configure it for static website hosting, and manage necessary permissions.

### Features:
- **Static Website Hosting**: The S3 bucket is configured to serve static HTML, CSS, and JavaScript files as a website.
- **Infrastructure as Code**: Terraform is used to define the entire infrastructure, making it easy to manage, update, and destroy the resources.
- **Access Control**: The bucket policy restricts access to public read-only, ensuring your site is available to everyone but protected from unwanted modifications.
- **Error Handling**: Custom error pages are supported in case users encounter issues while navigating the site.

## Prerequisites

Before you begin, ensure you have the following tools installed:

- [AWS CLI](https://aws.amazon.com/cli/) - To interact with AWS services.
- [Terraform](https://www.terraform.io/downloads.html) - To manage your infrastructure as code.

