# ansible_role_xorg

Install Xorg and all the required packages in ease

## Requirements

N/A

## Role Variables

```yaml
xorg:
  x11_keymap: gb pc105
  mouse_config: False
  XkbLayout: gb
```

## Dependencies

N/A

## Example Playbook

```yaml
- hosts: servers
  roles:
    - { role: ansible_role_xorg }
```

## License

GPLv3

## Author Information

John Stilia - stilia.johny@gmail.com
