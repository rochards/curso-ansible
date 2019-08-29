# Curso de Ansible

## Criação das máquinas virtuais com o vagrant
- $ vagrant up

## Conexão SSH nas máquinas
- $ vagrant ssh mysql     -> acessa máquina mysql
- $ vagrant ssh wordpress -> acessa máquina wordpress

## Verificar estado das máquinas
- $ vagrant status

## Executando o playbook
- $ ansible-playbook provisioning.yml -i hosts
