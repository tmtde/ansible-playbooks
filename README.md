## Install needed roles

```sh
ansible-galaxy install -g -f -r roles/requirements.yml
```

## Deploy playbook

```sh
ansible-playbook -i inventories/development/ docker-hosts.yml
```
