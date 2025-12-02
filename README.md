# Terraform EKS

Create EKS using Terrrarom

# Install AWS CLI
In the first step, we need to install AWS CLI, we will use the AWS CLI (``aws configure``) command to connect Terraform with AWS in the next steps.

Follow the (link)[https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html] to Install AWS CLI.

# Install and Connect Terraform with AWS
For installation Terraform you can refers to this (Link)[https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli]

## Configure with AWS
After installation has done, proceed to configure it by Running ``aws configure`` command and provide the AWS Security credentials as shown in the video.

# Initialize Terraform
Clone the repository and Run ``terraform init``. This will intialize the terraform environment for you and download the modules, providers and other configuration required.

# Optional, review the terraform configuration
Run ``terraform plan`` to see the configuration it creates when executed.

## Finally, Apply terraform configuation to create EKS cluster with VPC
```SH
terraform apply
```

