# setup environment

```
virtualenv ansible
source ansible/bin/activate
pip install -r requirements.txt
```

## run against workers
```
ansible-playbook -i inventory.yml  workers.yml
```