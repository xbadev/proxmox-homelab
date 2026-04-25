# Proxmox Homelab

Dedicated Proxmox VE hypervisor running on a repurposed Lenovo IdeaPad S540, serving as the foundation for VMs, containers, and security lab projects.

---

## Sections

| # | Section | Summary |
|---|---------|---------|
| 01 | [Installation](01-installation/) | Flashing the ISO, BIOS configuration, NVMe troubleshooting (RST → AHCI), and Proxmox installation |
| 02 | [Post-Install Config](02-post-install-config/) | Lid-close/sleep prevention for headless laptop operation, switching from enterprise to community repo |
| 03 | [Tailscale](03-tailscale/) | Installing Tailscale on the Proxmox host for secure remote access from any network |
| 04 | [Internal Network](04-internal-network/) | Creating vmbr1 isolated Linux bridge with static IPs for private VM-to-VM lab communication |
| — | [Windows 10 VM](windows10-vm/) | Creating and configuring a Windows 10 Pro VM with VirtIO drivers |
| — | [Ubuntu Server VM](ubuntu-server-vm/) | Ubuntu Server 24.04 LTS VM for security labs with VirtIO networking |

---

## What's Next

- Additional VMs and LXC containers
- Subnet routing and further Tailscale configuration
- Firewall rules and network segmentation
- Backup automation
- Monitoring and dashboards
