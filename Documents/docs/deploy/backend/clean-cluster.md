# Deploy Backend services on AKS: Clean cluster

## Pre-requisites

1. AKS created, up & running & kubectl configured to use it.
2. Helm installed locally, Tiller installed on cluster

**All tasks must be performed from `/Source/Backend/deploy/k8s` folder**

## Clean the AKS cluster

To clean the AKS cluster you can run the `clean.sh` script for Bash terminal or `Clean.ps1` for Powershell. This script do not accept any parameter.

Go to [Deploy Backend services on AKS main topic](../02-deploy-apis.md)