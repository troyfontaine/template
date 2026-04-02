# Project Overview

This project is a template for creating an Ansible role for a purpose. It includes a README.md file that provides an overview of the role, its requirements, variables, dependencies, and an example playbook. The role is licensed using the MIT License and includes author information for contact purposes.

## Folder Structure

- `.github/`: Contains GitHub-specific files, including the `copilot-instructions.md` file that provides instructions for using GitHub Copilot.
- `.lefthook`: Contains configuration for Lefthook, a Git hook manager.
- `defaults/`: Contains default variable definitions for the role.
- `files/`: Contains files that will be copied to the target hosts.
- `handlers/`: Contains handlers that can be triggered by tasks.
- `meta/`: Contains metadata about the role, including dependencies.
- `tasks/`: Contains the main tasks for the role.
- `templates/`: Contains Jinja2 templates that can be rendered and copied to the target hosts.
- `tests/`: Contains test playbooks and inventory for testing the role.
- `vars/`: Contains variable definitions that can be overridden by the user.

## Languages

- Ansible: The primary language used for writing the role.
- YAML: Used for configuration files and playbooks.
- Markdown: Used for documentation in the README.md file, Lefthook configuration and other instruction files.
- Jinja2: Used for templating in the `templates/` directory.
- Shell scripting: For Lefthook automation. May be used in tasks or handlers for executing commands on the target hosts.
- ini: Used for ansible.cfg and inventory files in the `tests/` directory.

## Files with Restrictions on Modifications

- `meta/main.yml`: This file contains metadata about the role, including dependencies. It should not be modified unless you are updating the role_name, adding or changing dependencies for the role.
- `README.md`: This file provides documentation for the role. It should be updated to reflect any changes made to the role, but the structure and format should be maintained.
