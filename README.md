## Setup
Make sure to copy `vars/default.yml.dist` to `vars/default.yml` and replace the properties.
Add a `hosts` file with the hosts to which you want to apply the TeamCity playbook.

## Run
The playbook doesn't have any dependencies, so you can run it directly:
```
ansible-playbook main.yml -i hosts -u <username> -kK 
```

