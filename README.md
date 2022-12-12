# S11-E2 Create Azure Resource Group using terraform
This code shows how to create Azure Resource Group using Terraform.  This is created for video S11-E2

## Step to run
1. Create a Service Principal in Azure.  See how to do this through [Azure Portal](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/guides/service_principal_client_secret#creating-a-service-principal-in-the-azure-portal) 

2. Create a file terraform.tfvars and provide Client-Id, Secret, Subscription and Tenant

3. Initialize Terraform

    >   terraform init

4. You can validate and see the plan

    >   terraform validate
    
    >   terraform plan

5. Now execute terraform

    >   terraform apply

