# AWS Security Templates

This repository contains CloudFormation templates for implementing AWS security best practices.

## Structure
- `iam/` - Identity and Access Management configurations
- `network/` - VPC and network security templates
- `storage/` - S3 bucket security configurations
- `monitoring/` - Security monitoring and logging
- `encryption/` - KMS and secrets management
- `waf/` - Web Application Firewall rules

## Usage
```bash
# Validate templates
./scripts/validate.sh

# Deploy stack
aws cloudformation create-stack --stack-name security-baseline --template-body file://main-stack.yaml