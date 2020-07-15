# Amazon-EKS
What is Amazon Elastic Kubernetes Service?

Amazon Elastic Kubernetes Service (Amazon EKS) is a managed service that makes it easy for you to run Kubernetes on AWS without needing to stand up or maintain your own Kubernetes control plane. Kubernetes is an open-source system for automating the deployment, scaling, and management of containerized applications.

An Amazon EKS cluster consists of two primary components:

The Amazon EKS control plane
Amazon EKS worker nodes that are registered with the control plane
The Kubernetes control panel plays a crucial role in a Kubernetes deployment as it is responsible for how Kubernetes communicates with your cluster — starting and stopping new containers, scheduling containers, performing health checks, and many more management tasks.

BASIC ARCHITECTURE FOR EKS

Basically, EKS means integration of Kubernetes with amazon services, EKS is almost fully automated service which works on the principle of Kubernetes Cluster or Master Salve Principle



Below is one Architecture which explains the working of what EKS actually do

No alt text provided for this image


In EKS service we have two option for running the services, this can be explained by this diagram shown below:-

No alt text provided for this image
We have two methods by which we can perform these services i.e. using AWS Fargate or using AWS Ec2 service.

A small project with the use of AWS EC2 service link:-



prerequisite for Amazon Eks Service

Some Basic knowledge about

Amazon web services:-

Amazon CNI - The Amazon VPC CNI plugin for Kubernetes supports a number of configuration options, which are set through environment variables. 

IAM- The IAM policies attached to the roles provide permissions for the cluster to interoperate with other AWS services on behalf of a user, give permissions to access other AWS resources, and perform actions when they run.

Kubernetes:-

Kubernetes cluster (master-slave principle) - It is a set of node machines for running containerized applications.

Kubectl - it is the command-line tool lets you control Kubernetes clusters
