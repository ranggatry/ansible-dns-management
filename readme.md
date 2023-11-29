## This script is for you who wants to automate DNS management in bind9 server 
### Apply new dns (update, add, delete)
```
ansible-playbook -i hosts deploy.yml
```

### Modify host list
```
vim hosts
```

### Modify NS list
```
vim group_vars/all.yml
```

### Adjust tld domain 
You must edit your tld domain from [ji] to your desired tld domain [.com/.net/.org]
```
vim templates/db-ji.conf.j2
vim templates/update_config.sh.j2
```
