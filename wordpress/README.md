# Maszyny 
5 maszyn
# W folderze głównym 
eval `ssh-agent`
ssh-add id.student  # pass: student1
# Uzupełnij hosts.ini publicznymi IP
# Uzupełnij files/nginx.conf
# Uzupełnij defaults/main.yml
# Uzupełnij tasks/nginx/config-ssl.yml
# Run with 
ansible-playbook -i hosts.ini infrastructure.yml
# Pray
