# Raspi-Hannover

Run the playbook:

```shell script
ansible-playbook system-setup.yml -i hosts
```

Only update the Docker containers:

```shell script
ansible-playbook docker-containers.yml -i hosts
```

## Install ansible modules

```shell script
ansible-galaxy collection install ansible.posix
```