# ansible-packages

This role will set up my minimal required packages on new servers (meant for internal use only)

This role requires ansible >= 2.9

## Install with Dependencies

    ansible-galaxy role install ofersadan85.packages --force

## Quick run

On a system with ansible installed, run the following command:

    ansible localhost -m include_role -a name=ofersadan85.packages

## Example Playbook

This is a simple role without variables

    - hosts: all
      roles:
        - ofersadan85.packages
