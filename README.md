# cloudcomputing-assignment3

All the steps to create Kubernetes cluster on AWS EC2 instance and deploying a sample serive on Kubernete cluster is captured in the document committed in the document section

All commands used to craete the cluster and corresponding output were attched as screen shots


Documentation Details :
=====================

MileStone -1
------------

For MileStone 1 Please refer to the document " Kubernetes_Cluster_Installtion under docs section 

Step by Step execution with all executable commands with screenshots mentioned in the document.

MileStone -2
------------

1. For MileStone 2 Please refer to the document " K8_Clusters_Using_Ansible" under docs section .
2. All the instruction with explanation is mentioned in the document
3. The aws-kubernetes-ansible folder contains all the necessary playbook files
4. Create your own key pair securities and name it ansible.pem and put it under "aws-kubernetes-ansible" folder
5. Create the cred.ym; file as mentioned in the document  "K8_Clusters_Using_Ansible" and put it  under "aws-kubernetes-ansible" folder
5. Execute the below command from  within aws-kubernetes-ansible folder to create the cluster
   sudo ansible-playbook setup.yml --ask-vault-pass

