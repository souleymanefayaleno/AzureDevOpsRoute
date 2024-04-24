# Azure-DevOps-Complete-Route

## Part 00 : What the Azure Cloud allows you to do
* Develop and deploy scalable cloud-native applications
* Create and manage infrastructure using cloud services such as networking, storage, and virtual machines
* Create IoT and edge solutions to improve operational efficiency or the quality of connected products and services
* Use AI and Machine Learning to add intelligent features to applications
* Identity and access management
* Design, manage and govern cloud solutions
* Use platform services to build, test, and deploy applications
* Manage IT resources or build applications from anywhere in on-premises, multi-cloud, and edge environments.
* Deploy and manage Linux infrastructure solutions
* Improve data and cloud infrastructure security
* Migrate infrastructure, application, and data workloads from on-premises data centers or other clouds to Azure
* Discover new cloud skills to achieve what you want today and in the future

## Part 01: Azure DevOps Basic Concepts
* What is Cloud Computing
* IaaS VS. PaaS VS. SaaS
* What is a Shared Responsibility Model
* What is a Traditional Build and Deployment workflow
* What is a Waterfall model in SDLC
* Problems with the traditional software development life cycle (SDLC)
* What is Agile, and how it solve the above challenges
* What is DevOps and Why It Matters
* What is CI/CD
* What is Azure DevOps and a quick walkthrough
* Creating an Azure DevOps Organization
* Creating an Azure DevOps Project
* Azure DevOps Pricing
* Azure DevOps hosting options: Azure DevOps Services VS Azure DevOps Server
## Part 02: Azure Boards and Agile Project Management 
* What are Azure DevOps Boards
* What are Azure board processes, agile, scrum, basic, and CMMI
* Managing work items in Azure boards
* Azure board implementation using basic process
* Working with teams, areas, and iterations
* Filters in backlogs and boards
* Azure board implementation using the scrum process
* Sprint planning and capacity planning
* Product backlog and taskboard
* Customizing Kanban boards
* Customizing dashboards
* Work item query
* Customizing team process
## Part 03: Git (VCS) and Source Control Management (SCM) in Azure DevOps 
* Introduction to Source Control and Azure Repos
* Git vs TFVC
* Configure Visual Code
* Cloning the repo
* Commit changes
* Reviewing history
* Working with branches
* Tagging a release
* Managing repository
* Managing Pull requests
* Sample application code
## Part 04: Build Pipeline
* Note: For the demo, we will be using the YouTube Clone website
* Provision Azure App Service to host the website.
* Creating Build Pipelines using the classic editor
* Creating build pipeline using YAML
* YAML pipeline structure, the difference between jobs, stages, steps, and tasks
* Creating a multi-stage CICD pipeline
* variables, triggers, Build properties, agents
* Publishing and Download Build Artifacts
## Part 05: Continuous Delivery with Azure DevOps Release Pipeline
* Note: this is a continuation of the previous video.
* Automating Deployment with a multi-stage Release Pipelines
* Continuous Deployment Triggers
* Continuous delivery using deployment slots to enable Blue-Green deployment
* Deployment gates such as Query Work Items and Approvals before the prod deployment
* Update the code to test the entire CICD process with the Build and Release pipeline
## Part 06: Azure Test Plans and Testing
* Note: We will be using the Youtube Clone website to implement the below steps
* Azure Test Plan Overview
* Features of Azure test plan
* Managing Test Plans, Suites and Cases
* Subscribe to the test plan free trial
* Authoring, Running, and Analyzing Manual Tests
* Azure Test and Feedback extension
## Part 07: Basic Project Artifacts with Azure Artifacts
* Note: In this video, we will use a Nike Landing page as a sample application for CICD using Azure Artifacts
* Overview of Azure Artifacts
* Create the Azure DevOps project and check out the application code
* Set up the infra using Azure Web App
* Create Azure Artifacts feed to host the packages
* Create the CI pipeline that builds the package and pushes it to the feed
* Create the CD pipeline that consumes the package
* Promote the package to trigger the release pipeline
* Upstream packages in Azure Artifacts
## Part 08: Infrastructure as Code (IaC) with Terraform and Azure DevOps
* Introduction to IaC and Tools
* Various Terraform commands and workflow
* Creating Terraform configuration files
* Setting up terraform backend with Azure storage
* Executing Terraform commands using CLI
* Azure DevOps CI Pipeline to init, plan, and archive the plan file
* Azure DevOps CD pipeline to apply the changes
## Part 09: Self Hosted agents on Azure Virtual machine scale sets
* Microsoft-hosted vs. self-hosted agents
* Use case of self-hosted agents
* Ways to set up self-hosted agents: VM, VMSS, container
* What is a Virtual machine scale set
* Set up a self-hosted agent using VMSS
* Register the agent on an agent pool
* Install custom utilities on the agent
* Use the self-hosted agent on a pipeline
* Comparison between self-hosted and Microsoft-hosted agents
* Work folder walkthrough on agent
## Part 10: Managing Containers with Azure DevOps
* What is a container
* Understanding Virtual machine V/s Containers.
* Challenges with the non-containerized applications
* Docker Architecture
* Containerize a sample To-Do list web app written in React JS.
* Benefits of a multi-stage docker file
* What are Azure container instances(ACI)
* Azure DevOps CICD Pipeline to deploy to ACI
## Part 11 Implementing end-to-end CICD using Azure DevOps on Kubernetes.
* Basic Introduction of Kubernetes and its benefits
* Kubernetes Architecture
* What is the control plane and its components
* What are Nodes and types of Nodes
* What is a Pod/Deployment/Service
* Azure DevOps CICD Pipeline for a web app running on Kubernetes
* Sample application: My Health Care - Microservices-based Healthcare management app
## Part 12 Security and Permissions in Azure DevOps
* Enabling advanced security in Azure DevOps
* Dependency Scanning
* Secret scanning and managing alerts
* How to use secrets in your pipeline
* Code scanning for vulnerabilities
* Sample Application: My Health Care - Microservices-based Healthcare management app
## Part 13: Serverless app CICD
* Introduction to Azure functions
* Use case and benefits of an Azure function
* Introduction to the sample app to be used for this demo: Serverless QR Code Generator
* Demo creating the Azure function and deploying locally
* Publishing the function to Azure using CLI tools
* Build and release pipeline for building and deploying the code to Azure Functions
## Part 14: Azure DevOps wiki
* Overview of wiki
* Creating and editing a project Wiki
* Publishing code as Wiki
* How we can use Azure DevOps wiki to collaborate on a project
## Part 15: Azure DevOps Security best practices
* Azure DevOps Access Control
* Organization Settings
* Agent pools Management
* Pipeline settings
* Project-level Settings
* Pipeline security
* Repo settings
* Authentication and Authorization
* Secrets and credentials access
## Part 16: Issue and troubleshooting Azure DevOps
* In this video, we will discuss the most common issues you have faced throughout the series and solutions to those. 
## Part 17: Bonus Video: Azure DevOps Scenario-based Interview Questions
* In this video, we will discuss the most asked scenario-based interview questions and answers for Azure DevOps
