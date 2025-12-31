# Terraform AWS Ubuntu Web Server

## 專案介紹
使用 Terraform 在 AWS 上建立 Ubuntu EC2 Web Server，包含：
- 最新 Ubuntu 22.04 AMI
- VPC 與subnet
- Security Group (SSH + HTTP)
- Key Pair（使用者提供 public key）
- 自動部署範例網頁 (Apache)
