<h1 align="left"> Ansible Automation Projects

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue)](https://www.linkedin.com/in/aubinazuriah995?trk=profile-badge)
<img src="https://img.shields.io/static/v1?label=%F0%9F%8C%9F&message=If%20Useful&style=style=flat&color=BC4E99" alt="Star Badge"/>
<a href="https://github.com/sudoesjudo/automation/stargazers"><img src="https://img.shields.io/github/stars/sudoesjudo/automation" alt="Stars Badge"/></a>
<a href="https://github.com/sudoesjudo/automation"><img src="https://visitor-badge.laobi.icu/badge?page_id=sudoesjudo.automation" alt="Visitor Badge"/></a>


###### This README is still in progress. Updates are being made as time permits

Hello! I'm Aubin 👋 Nice to meet you! Welcome to my first public Repository. 

Let's build, automate, and make life a bit simpler.

Here, I'll be working on automation scripts and fun networking projects.<br/>
This repository contains Ansible playbooks and roles designed to automate network configuration changes amongst other repatitive tasks.

## Features:
- **Playbooks**♻️📘: Automate things that take too much time and could bore the best of us
- **Role Assignment**☝️✌️🗒️: Modular, reusable Ansible roles                   
- **Scalability**📈: Works for small to large-scale infrastructures

## Automation Project Directory Structure

```plaintext
automation/                 # Root folder of project
├── ansible.cfg                # Ansible configuration file
├── inventory/                 # Inventory files
│   ├── hosts                    # Main inventory file listing devices
│   └── group_vars/              # Group-specific variables
├── playbooks/                 # Directory for playbooks
│   ├── site.yml                 # Main playbook
│   └── deploy.yml               # Playbook for deployment
├── roles/                     # Directory for roles
│   ├── common/                  # Role for common tasks
│   │   ├── tasks/                 # Main tasks file
│   │   ├── vars/                  # Variables specific to the role
│   │   └── templates/             # Jinja2 templates
│   └── sites/                 # Role for sites
│   │   ├── devices/             # Devices inside sites
│   │   │   ├── routers.yml        # Routers and their configs
│   │   │   ├── switches.yml       # Switches and their configs
│   │   │   ├── firewalls.yml      # Firewalls and their configs
│   │   │   ├── servers.yml        # Servers and their configs
│   │   │   └── vms.yml            # Virtual Machines and their configs
│   │   ├── tasks/               # Tasks related to sites
│   │   ├── vars/                # Variables for sites role
│   │   └── templates/           # Jinja2 templates for sites role
└── venv/                     # Python virtual environment
```

## Naming Schema and Assignments
###### This will change and update over time 
  

| admin_tasks     | managed_devices | fetch_configs | push_configs  | interface_congifs |
|:---------------:|:---------------:|:-------------:|:-------------:|:-----------------:|
| firmware_update | get_heartbeat   | vlan_config   | add_new_vlan  | show_up_down      |
| backup_config   | show_version    | get_routes    | add_static_rt | show_counters     |
| pull_firmware   | reload_now      | show_ospf     | add_ip_addr   | show_erros        |
| save_config     | list_hosts      | show_bgp      | add_new_svi   | ip_addr           |


Old School Visit Counter:

![Visitor Count](https://profile-counter.glitch.me/sudoesjudo/count.svg)



              







