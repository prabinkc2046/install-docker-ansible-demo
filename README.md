# Ansible Playbook: Package Update, Docker Installation, and Hello-World

This repository contains an Ansible playbook to automate the process of updating package indexes, installing Docker, and running the Docker "hello-world" container on remote servers.

## Usage

1. Clone this repository to your local machine:

 ```bash
git clone https://github.com/yourusername/install-docker-ansible-demo.git
cd install-docker-ansible-demo
```

Update the inventory.ini file with the hostnames or IP addresses of your target servers.

Run the playbook to update packages, install Docker, and run the "hello-world" container:

```bash
ansible-playbook -i inventory.ini install_docker.yml
```

## Notes
Review and customize the playbook according to your environment and requirements.
Ensure you have Ansible installed on your local machine.
Make sure you have SSH access to the target servers with appropriate privileges.

## License
This project is licensed under the MIT License.

