# ansible
=======

My own collection of ansible things and learnings.

This repo assumes that you have used git@github.com:thehar/thehar-vagrant.git to build a VM in Virtualbox using vagrant, have ssh keys set in the vagrant user and vagrant installed on your local machine.

## Jenkins

#### Steps
1. git clone git@github.com:thehar/ansible.git
2. cd ansible
3. ansible-playbook -i hosts -u vagrant site.yml