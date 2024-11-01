## Command to run to launch the installer
`ansible-playbook -i hosts.yml --ask-become-pass my-installer.yml`

### Install DWM
`ansible-playbook -i hosts.yml --ask-become-pass my-installer.yml -e "is_virtual_machine=true"`

### If you are running locally you can do
`ansible-playbook -i hosts.yml --ask-become-pass my-installer.yml --connection=local`

