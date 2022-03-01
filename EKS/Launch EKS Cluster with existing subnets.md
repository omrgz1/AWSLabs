# AWS Launch Wizard - Deployment using AWS Console
AWS Launch Wizard for Amazon Elastic Kubernetes Service (Amazon EKS) guides you through the sizing, configuration, and deployment of an Amazon EKS control plane, connecting worker nodes to the cluster, and configuring a bastion host for cluster admin operations. 

https://docs.aws.amazon.com/launchwizard/latest/userguide/what-is-launch-wizard-eks.html

# AWS EKS QuickStart - Deployment using AWS EKS Quickstart (CFN Tempalte)
## Quickstart Landing Page
https://aws.amazon.com/quickstart/architecture/amazon-eks/
Select Deploy using AWS CloudFormation > Deploy into an existing VPC
## Quickstart GitHub Repo
https://github.com/aws-quickstart/quickstart-amazon-eks

# CloudFormation EKS Documentation & Example Configuration
https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-eks-cluster.html

## ResourcesVpcConfig
The VPC configuration that's used by the cluster control plane. Amazon EKS VPC resources have specific requirements to work properly with Kubernetes. For more information, see Cluster VPC Considerations and Cluster Security Group Considerations in the Amazon EKS User Guide. You must specify at least two subnets. You can specify up to five security groups, but we recommend that you use a dedicated security group for your cluster control plane.

# Creating an EKS Cluster using EKSCTL
eksctl is a simple CLI tool for creating and managing clusters on EKS
https://eksctl.io/

## EKSCTL GitHub Repo with Examples
https://github.com/weaveworks/eksctl/tree/main/examples

## ETKCTL Existing VPC Example
https://github.com/weaveworks/eksctl/blob/main/examples/04-existing-vpc.yaml

