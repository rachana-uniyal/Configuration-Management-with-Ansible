# Configuration-Management-with-Ansible


## 1. Automate Node.js application Deployment 

### Technologies used:
Ansible, Node.js, DigitalOcean, Linux 

### Project Description: 
- Create a Server on DigitalOcean 
- Write Ansible Playbook that Installs necessary technologies, creates Linux user for an application and deploy Node.js application with that user 


## 2. Automate Nexus Deployment 

### Technologies used:
Ansible, Nexus, DigitalOcean, Java, Linux 

### Project Description:
- Create Server on DigitalOcean 
- Write Ansible Playbook that creates Linux user for Nexus, configures server, installs and deploys Nexus, and verifies it is running successfully


## 3. Ansible & Docker

### Technologies used:
Ansible, AWS, Docker, Terraform, Linux

### Project Description:
- Create AWS EC2 Instance with Terraform
- Write Ansible Playbook that installs necessary technologies like Docker and Docker Compose, copies docker-compose file to the server and starts the Docker containers configured inside the docker-compose file

## 4. Ansible Integration in Terraform

**Technologies used:** Ansible, Terraform, AWS, Docker, Linux

1. Create Ansible Playbook for Terraform integration.
2. Adjust Terraform configuration to execute Ansible Playbook automatically.
   - Once Terraform provisions a server, it will execute an Ansible playbook that configures the server.
You can find the code project on the [ansible branch](https://github.com/rachana-uniyal/IaC-with-Terraform/tree/ansible) of the GitHub repository.

## 5. Configure Dynamic Inventory

**Technologies used:** Ansible, Terraform, AWS

### Project Description:

1. Create an EC2 Instance with Terraform.
2. Write an Ansible AWS EC2 Plugin to dynamically set the inventory of EC2 servers that Ansible should manage.
   - Instead of hard-coding server addresses in the Ansible inventory file, the plugin will handle it dynamically.

You can find the code for this project on the [deploy-to-ec2 branch](https://github.com/rachana-uniyal/IaC-with-Terraform/tree/deploy-to-ec2) of the GitHub repository.

## 6. Automate Kubernetes Deployment

**Technologies used:** Ansible, Terraform, Kubernetes, AWS EKS, Python, Linux

### Project Description:

1. Create an EKS cluster with Terraform.
2. Write an Ansible Play to deploy an application in a new Kubernetes namespace.

You can find the code for this project on the [eks branch](https://github.com/rachana-uniyal/IaC-with-Terraform/tree/eks) of the GitHub repository.









