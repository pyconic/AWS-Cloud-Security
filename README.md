# AWS-Cloud-Security
AWS Cloud Security Project utilizing IAM.

# Overview
This project involves using AWS Identity and Access Management (IAM) to enhance cloud security by managing access to AWS resources effectively. The focus is on using IAM policies to control permissions based on environment-specific tags, providing secure and restricted access to different AWS resources.

# Project Goals
* Implement **AWS IAM Policies**: Create IAM policies to manage user access to EC2 instances based on their environment (e.g., development or production).
* Use **Tags** for Resource Management: Apply tags to EC2 instances to categorize resources and control access based on these tags.
* **Test** and **Troubleshoot** Policies: Verify the effectiveness of policies by attempting actions that should be allowed or denied, such as stopping instances.

# What is AWS IAM?
AWS IAM (Identity and Access Management) lets you securely manage access to AWS services by controlling user permissions, ensuring only authorized users can access specific resources, enhancing overall security.

# Tags in AWS
Tags are labels that help AWS account users identify and organize their resources. They are useful for managing large groups of resources and enforcing security policies. In this project, tags like "Env" with values such as "production" or "development" were applied to categorize instances.
