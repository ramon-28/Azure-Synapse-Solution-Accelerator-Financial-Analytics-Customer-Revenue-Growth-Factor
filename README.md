privacidad ---
page_type: sample
languages:
- python
products:
- azure-synapse-analytics
- azure-machine-learning
- power-bi
---

![Customer Revenue Growth Factor Solution Accelerator](./Resource_Deployment/imgs/CustomerRevenueGrowthFactor.png)

# Customer Revenue Growth Factor Soltion Accelerator
This accelerator was built to provide developers with all of the resources needed to build a solution to identify the top factors for revenue growth from an e-commerce platform using Azure Synapse Analytics and Azure Machine Learning.


## Getting Started 
Start by deploying the [resources](./Resource_Deployment/ResourceDeployment.md) needed for this solution: 

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmicrosoft%2FAzure-Synapse-Solution-Accelerator-Financial-Analytics-Customer-Revenue-Growth-Factor%2Fmain%2FResource_Deployment%2Fazuredeploy.json)

1. Clone this repository and navigate to the root of the directory  
2. Go to [Deployment guide](./Resource_Deployment/README.md) for the steps you need to take to deploy this solution 

## Prerequisites
In order to successfully complete your solution, you will need to have access to and or provisioned the following:
1. Access to an Azure subscription
2. A Power BI Pro License (or free trial)

Optional
1. Azure Storage Explorer

## Azure and Analytics Platform
The directions provided for this repository assume fundemental working knowledge of Azure, Azure Synapse Analytics, Azure Machine Learning Services, and Power BI.

For additional training and support, please see:
 1. [Azure Synapse Analytics](https://azure.microsoft.com/en-us/services/synapse-analytics/)
 2. [Azure Machine Learning Services](https://azure.microsoft.com/en-us/services/machine-learning/)
 3. [Power BI](https://docs.microsoft.com/en-us/power-bi/)

## Process Overview  

The architecture diagram below details what you will be building for this Solution Accelerator:

![Azure Synapse AI Architecture](./Reference/Architecture/SynapseArchitecture.png)
![Azure Synapse AI + AutoML Architecture](./Reference/Architecture/SynapseAutoMLArchitecture.png)

### [Resource Deployment](./Resource_Deployment)
The resources in this folder can be used to deploy the required resources into your Azure Subscription. You can do this in the Azure Portal

### [Analytics Deployment](./Analytics_Deployment)
This folder contains the Notebooks needed to complete this solution accelerator. Once you have deployed all the required resources from ResourceDeploymnet.md, run through the Notebooks following the instructions in [Resource Deployment](./Resource_Deployment). 

## License
Copyright (c) Microsoft Corporation

All rights reserved.

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the ""Software""), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED AS IS, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE


## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
