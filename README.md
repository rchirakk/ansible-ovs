# ansible-ovs

ansible role to install Open vSwitch(OVS)

# Requirements
none

# Role variables
```
validate_certs: cert validation
rpm_url: ovs rpm: rpm url
deb_ovs_switch_url: debian url
deb_ovs_common_url: debian url
```

# Example Playbook
```
- hosts: all
  become: true
  roles:
    - role: ansible-ovs
```

# Testing