# Azure App Service Request

This module is supplied by the cloud platforms team for all App Service instances on Azure.
Please note that all requests for App Service instances that bypass this module will be blocked by default. 

If this module does not do what you need, please raise an issue or even better a pull request!

## Usage

The following inputs are required for this module: 
- App name
    - This is used as a unique identifier for your application in our Azure tenancy
    - Please use the syntax teamName-projectName-appName
- Description
    - A single sentence describing the purpose of the application
- Environment
    - Please tag appropriately with the following options:
    - dev, test, stage, prod
- Owner
    - This should be your internal ID or project ID if you are a contractor. 
