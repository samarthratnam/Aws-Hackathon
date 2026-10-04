# AWS Compute Optimizer Driven Rightsizing Programme

## Team Members

| Student ID | Name |
|---|---|
| 2400032408 | **Prem Prakash** |
| 2400031777 | **Tentu Divya Amrutha** |
| 2400031637 | **Chimakurthi Lakshmi Janani** |
| 2400031630 | **Samarth V Ratnam** |

---

## 📌 Project Overview

The **AWS Compute Optimizer Driven Rightsizing Programme** is a cloud cost-optimization project focused on identifying inefficiently provisioned AWS resources and determining whether they can be resized according to their actual workload requirements.

Cloud resources are often provisioned with more capacity than necessary to avoid performance issues. While this provides additional capacity, unused resources still generate unnecessary costs.

This project explores a continuous rightsizing workflow using:

- **Amazon EC2** for compute resources
- **Amazon CloudWatch** for resource monitoring
- **AWS Compute Optimizer** for optimization recommendations
- **AWS IAM** for access control

The core idea is:

```text
AWS Resources
      ↓
Resource Usage
      ↓
Amazon CloudWatch
      ↓
AWS Compute Optimizer
      ↓
Optimization Recommendations
      ↓
Evaluate Cost & Performance
      ↓
Rightsize Resource
      ↓
Monitor Again
      ↺
