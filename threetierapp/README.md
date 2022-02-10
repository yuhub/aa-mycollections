# Ansible Collection

## Mycollections namespace

1. mycollections directory structure

    ```
    mycollections/
    └── threetierapp   
        ├── README.md
        ├── galaxy.yml
        ├── playbooks
        │   ├── config.yml 
        │   ├── in_memory_inventory.yml 
        │   ├── instances_vars.yml
        │   └── provision.yml
        ├── plugins
        │   └── README.md
        └── roles
            ├── apache
            ├── firewall
            ├── haproxy
            └── mysqldb

### Playbooks
mycollection.threetierapp collection contains three playbooks.

1. provision.yml
2. in_memory_inventory.yml
3. config.yml

### Roles
mycollection.threetierapp collection contains four roles.

1. firewall
2. apache
3. haproxy
4. mysqldb
