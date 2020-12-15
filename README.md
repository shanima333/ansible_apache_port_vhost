# Ansible - Setup a server and Host a simple php website

Playbook to install apache and configure a website

##Files

  - apache-vhost.yaml 
  - hosts
  - httpd.conf.tmpl
  - vhost.tmpl
  

# apache-vhost.yaml 
Whole task written in a single Playbook 
### 6 tasks
  -  Install apache and php
  - Update apache configuration file
  - Create Vhost file
  - Create website document root
  - Upload website files
  - Restart services

## hosts
 - lists the hosts with ansible_user and ansible_ssh_private_key_file
 
## httpd.conf.tmpl

Template  for httpd configuation file

## vhost.tmpl

Template for vhost configuration file 

## Folder

 - website
Which contains the website files
