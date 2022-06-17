#

to run: 
```
vagrant up

vagrant ssh-config > load the file location into inventory.ini
```
ansible-galaxy collection install ansible.windows
ansible-playbook playbook.yml 
```
play