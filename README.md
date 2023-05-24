# TERRAFORM - AWS resources

This GitHub repo contains basic Terraform building blocks for the Azure cloud. 

>Note: This is not meant for production!!!


## Providers

| Name | Version |
|------|---------|
| aws | ~>3.0 |
| random | ~>3.0 |
| tls | ~>4.0 |
| null | ~>3.0 |


### Deployment Instructions
* Clone this repository
* Edit ```terraform.tfvars``` to match your values.
* Delete the ```.tf``` files that contain resources that you don't need.
* Run ```terraform init``` to download the Azure provider.
* Run ```terraform plan``` to view the plan.
* Run ```terraform apply``` and wait a couple of minutes until the resources created in the Azure cloud.


## Resources used and links to the relevant Terraform websites where you can find more information about further options.

| Name | Type |
|------|------|
| [azurerm_resource_group.azure-rg](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/resource_group) | resource |

