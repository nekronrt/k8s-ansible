# Configuracion de Zona Horaria y NTP


## Para instalar plugins
This plugin is part of the community.general collection (version 4.2.0).

You might already have this collection installed if you are using the ansible package. It is not included in ansible-core. To check whether it is installed, run ansible-galaxy collection list.

To install it, use:


        ansible-galaxy collection install community.general.


To use it in a playbook, specify: community.general.timezone.


## correr playbook

ansible-playbook -i inventory ntp_playbook.yml --u kadmin --ask-become-pass
