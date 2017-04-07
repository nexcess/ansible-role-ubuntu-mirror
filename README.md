# Ansible Role: Ubuntu Mirror

Installs the Ubuntu mirroring role

## Requirements

None.

## Role Variables

See `defaults/main.yml`.

## Dependencies

nexcess.mirror

## Add to Requirements

    - src: https://github.com/nexcess/ansible-role-ubuntu-mirror.git
      name: nexcess.ubuntu-mirror

## Example Playbook

    - hosts: servers
      roles:
        - nexcess.ubuntu-mirror

## License

MIT / BSD
