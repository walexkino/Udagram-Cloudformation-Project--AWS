# Udagram-Cloudformation-Project-AWS

This project is about deploying web servers for a high-availability web
app in two Availability Zones using CloudFormation on AWS.

## Project Introduction

In this project, papy's company wants to deploy a travelling Web app
called Udagram to AWS infrastructure. As the DevOps engineer, I
proceeded to deploy a web server for a highly available web app using
CloudFormation. I also wrote scripts that create, update and delete the
infrastructure and application for the Web App.

The script starts with the deployment of the complex networking
components, security roles and Web App.

## Architecture Diagram

![DIAGRAM OF UDAGRAM PROJECT ARCHITECTURE](https://user-images.githubusercontent.com/33078258/181122105-5236b16e-1aa7-4775-a06b-3ed264c84153.png)


## File contents
```sh
-> /web app: This folder contains the app code for the Udagram
Projects and all of its dependencies.

-> /Deployment screenshot: This includes the screenshots of the
infrastructure and app.

-> create.sh: This is a shell script that creates the CloudFormation
stack.

-> update.sh: This script updates the CloudFormation stack.

-> delete.sh: This script makes it easy to remove the CloudFormation
stack

-> udagram-template.yml: This template for the Udagram project
cloudFormation script.

-> udagram-parameter.json: This parameter declaration for the
Udagram project cloudFormation script.
```

## HOW TO DEPLOY 

Run:
```sh
./create.sh stackname udagram-template.yml udagram-parameter.json
```

## Screenshot of the web app
![18  Screenshot of the Udagram Web app](https://user-images.githubusercontent.com/33078258/181128317-12d71d20-8521-4c89-afbd-b3e912d991dc.png)


Thank you.
