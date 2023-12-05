# ssh-hardening
Ansible playbook that hardens/increases security with SSH(Ciphers, MACs, and Key Exchange).

Update inventory/hosts file accordingly.

Run with command:
ansible-playbook -i inventory/hosts main.yml -uusername -K --ask-pass