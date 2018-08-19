# AnsibleLB

#checking the servers availability
ansible -i development.txt -m ping all


#Executing playbook
ansible-playbook  -i development.txt loadbalancer.yml 
