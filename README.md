# Azure.Basics

## Azure Portal
https://portal.azure.com/#home

![image](https://github.com/rafaelxoliolab/Azure.Basics/assets/63336526/93454be2-3ef6-4d34-a44f-66321d20952d)



## Azure Resource Manager (ARM)
- ARM is the deployment and management service for Azure.
- It provides a management layer that enables you to CRUD resources in your Azure Account
- Features managemente provices acces control locks and tags, to secure and organizae your resources after deployment.

- ![image](https://github.com/rafaelxoliolab/Azure.Basics/assets/63336526/63fd75ce-f56f-4099-bcbd-7a22d27ed051)

### Key terms

#### Azure Interfaces

All clients and interfaces are handled through the same API
- __Azure Portal__ Web-base user interface
- __Azure Powershell and CLI__ Client to automate resource management
- __REST Clients__ Allow for custom resource management solutions
- 
#### Resource
- An item or service that can be provisioned in Azure. VM, DBs web apps, storage accounts

#### Resource Group
- A container with related resources for Azure Solution. Includes Those resources that you want to manage as a group.

#### Azure Account
- Azure.microsoft.com

#### Declarative Syntax

- __ARM Templates__ A JSON file that defines one or more resources to deploy to a Resource group.
- __Bicep__ A file for declaratively deploying Azure resources.

#### Azure CLI

https://learn.microsoft.com/en-us/cli/azure/

Download from:
https://learn.microsoft.com/en-us/cli/azure/install-azure-cli-windows?tabs=azure-cli

- Set PATH environment variable on your system
  - Open the Start menu and search for "Environment Variables"
  - Click "Edit the system environment variables"
  - Click the "Environment Variables" button
  - Under "System Variables", scroll down and find "Path"
  - Click "Edit" and add the installation path of Azure CLI at the end of the list (e.g., C:\Program Files (x86)\Microsoft SDKs\Azure\CLI2\wbin)




