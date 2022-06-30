# Build a Website Login page with AWS ELB and AWS Cognito using Terraform CDK

This repository describes how to integrate Amazon Cognito User Pool(OAuth 2.0 Client credentials grant) and Application Load balancer(Cognito Authorizer) using Terraform CDK. This sample is applicable to a usecase for user login authentication. All resources and configuration is provided through Terraform CDK(typescript codes).

## Overview

You call build a website with a simple Login button.

## Prerequisites

If you haven't already done so you must first:

- [Install Terraform and CDKTF](https://learn.hashicorp.com/tutorials/terraform/cdktf-install)
- Generate an ACM Certificate that will be used to secure communication between the browser and ALB using HTTPS. (AWS Cognito required ALB with HTTPS listener.)
- 