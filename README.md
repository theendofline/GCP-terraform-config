# GCP-terraform-config


### Resources visualisation: 

![alt text](https://cdn.qwiklabs.com/tQ3NS2xpirSs1UXVcklIYVQM7WkUc%2F8iC7ryGFPSfRs%3D)

## Overview
This project contains Terraform configurations for setting up cloud resources. The structure uses modularized `.tf` files for efficient and reusable infrastructure as code.

## Prerequisites
- Cloud Shell and project access

## Getting Started

### Set Up Environment

1. **Open your Cloud Shell**

2. **Create a Directory for Configuration Files:**
   ```bash
   mkdir path/to/your_dir_name
   cd path/to/your_dir_name
   ```

3. **Initialize Terraform:**
   ```bash
   terraform init
   ```

### Configuration

- **Create Configurations:**

  Create `.tf` configuration files for all required resources. Organize these files using nested folders for modules, which are containers for reusable configurations. For instance, use the `instance` directory for Virtual Machines (VMs).

- **Format Configuration Files:**

  To format the Terraform configuration files to a canonical format and style, run:
   ```bash
   terraform fmt
   ```

### Deployment Process

1. **Initialize Terraform:**
   ```bash
   terraform init
   ```

2. **Create an Execution Plan:**
   ```bash
   terraform plan
   ```

3. **Apply Changes:**
   ```bash
   terraform apply
   ```

## Usage
You can use it as a start simple template for your infrastructure. For more 
details see the [Terraform documentation ](https://developer.hashicorp.com/terraform/tutorials/gcp-get-started/google-cloud-platform-build)

## Contributing
Any advice or contributions are welcome!