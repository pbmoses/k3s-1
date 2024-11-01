# k3s-1 
Ansible to assist in installation of k3s on raspberrypi. 

Initial k3s cluster on (1) Raspberry Pi 4 and (2) Raspberry Pi 3

Raspian was used as the OS to expedite the process. 
Customizations needed:
  - cgroup_enable=cpuset cgroup_memory=1 cgroup_enable=memory ---> append to /boot/firmware/cmdline.txt
  - Helm --> to install Grafana Alloy
  - Ansible --> to build automation
  - ssh enabled at image creation time (to allow for headless access)

raw_playbooks are placeholders until I build roles. 
