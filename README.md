# JCON 2018 - Containerized test automation
This repository contains all sources of my Talk *Containerized test automation*
on the JCON 2018.

## Repository structure

* paas  
  This directory contains everything required to setup the paas infrastructure.
* infra  
  Contains the infrastructure configuration to build the sample app.
* src  
  Contains the source code of the sample app
  
## Setup
A minishift setup is required on your local machine.
The project setup is mostly automated via the bootsrap.sh script in the *paas* folder.
Please have a look at the script for the manual import of the todo-app repository
into the local gogs setup. After cloning/forking the repository and setting up the paas, 
it may be required to change the repository references in the *infra* configuration files
depending on the user name you've chosen for your gogs installation.