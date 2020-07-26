# msa-devops-2020

This devops project was created to understand the process of continuous integration and continuous delivery using Azure Pipeline. A basic react app using typescript was created to understand how the process of continuous build and deployment is implemented on a project.  The complete process has been described in detail in the below steps.

A basic react application was developed using typescript and added to a new repository ‘https://github.com/vinivarghese/msa-devops-2020'. 
A new web app service was created in Azure with the url ‘https://vini-msa-2020-devops.azurewebsites.net'. 
A new organisation ‘vini-msa-devops-2020’ was created on Azure DevOps 
A new pipeline was created and initialized with GitHub YAML and linked to the GitHub repository ‘https://github.com/vinivarghese/msa-devops-2020'
A new release pipeline ‘MSA-DevOps-2020’ was created for taking the build artifact from our build pipeline and deploying it
A continuous deployment trigger was enabled on the release pipeline
Few changes were made on the react application to test our build and release pipelines 
The updates were visible when navigated to the web app via the url ‘https://vini-msa-2020-devops.azurewebsites.net'
