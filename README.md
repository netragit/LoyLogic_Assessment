# LoyLogic_Assessment

# Commited by: Netra Kalyanshetty
Description: As per assessment given repository consists of the following folders.

1. Cloudformation
2. Ansible
3. Jenkins file

**Cloudformation:**
It contains template which will launch two different stacks:
Networking Stack: VPC, Public and Private Subnet, Public and Private Route Table, Internet Gateway and Nat Gateway.

**Compute Stack:** It will launch 2 servers.
1. EC2 Server: Which will launch an Amazon Linux 2 instance and install the jenkins and Ansible through user data.
2. Target Server: Will launch Amazon Linux 2 instance.
	
**Jenkins file:**
Jenkins file is created using Pipeline, It contains pipeline script.
	Step 1: Integration with git repository.
	Step 2: Build the java application.
	Step 3: Running the Playbook yaml file.
	
**Ansible:**
Ansible folder contains playbook.yaml file and host file.

Playbook.yaml file:
1. Module is defined which will copy the jar file from jenkins server to target server.

Hosts.ini file:
Target related information is stored in host file.
