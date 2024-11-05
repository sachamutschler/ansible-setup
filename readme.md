#Steps to fast setup your Env (Git/GitFlow/HomeBrew/DDev)

#1 - Requirements : (Ansible)
Command to install Ansible with python installed by default on Mac :
```bash
python3 -m pip install --user ansible
```

#2 - Clone the project
SSH :
```bash
git clone git@github.com:sachamutschler/ansible-setup.git
```

#3 - Start the playbook
```bash
ansible-playbook -i inventory playbook.yml
```

You can avoid installing a package by removing one of the tasks in playbook.yml if needed.