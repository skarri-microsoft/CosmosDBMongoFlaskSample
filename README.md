# Python Flask sample for Cosmos DB Mongo using Azure App Service (Linux) & Flask Mongoengine 0.9.5

This is a minimal sample app that demonstrates how to run a Python Cosmos DB Mongo API Flask application on Azure App Service on Linux.

* Please create a Azure Cosmos DB Mongo API account in Azure portal. Here is the link to know more about this https://docs.microsoft.com/en-us/azure/cosmos-db/mongodb-introduction
* To deploy this application we are going to use az cli, please install it if you don't have it on your box. https://docs.microsoft.com/en-us/azure/cosmos-db/mongodb-introduction
* Clone this repo and Cd into the directory "CosmosDBMongoFlaskSample"
* update line no:9 and 11 in application.py with Cosmos DB Mongo API Credentials and save it.
* Run the following az commands:
az login
az account set --subscription subid
az webapp up --sku F1 -n yourwebappname