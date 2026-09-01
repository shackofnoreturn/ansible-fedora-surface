# Ansible Fedora Surface
*Ansible project to provision and set up Fedora distribution on a Microsoft Surface machine.*


## What


## How


## Tasks
- [ ] Task 1



# ansible-fedora-surface

Ansible automation for Microsoft Surface devices running Fedora KDE Plasma.

This repository contains Surface-specific configuration and hardware support.

Generic Linux configuration is intentionally kept in the separate
`ansible-linux-common` repository.

## Target hardware

Initial target:

- Microsoft Surface Pro 7+

## Target operating system

- Fedora KDE Plasma
- Wayland

## Surface support

This repository manages the Linux Surface stack, including:

- Linux Surface repository
- Surface kernel
- IPTS
- Touchscreen
- Surface Pen
- Type Cover
- Touchpad
- Rotation
- Power management
- Suspend/resume configuration
- KDE tablet configuration
- Secure Boot
- Firmware configuration
- Hardware validation

## Repository structure

```text
ansible-fedora-surface/
├── ansible.cfg
├── inventory/
├── group_vars/
├── host_vars/
├── playbooks/
├── roles/
└── README.md