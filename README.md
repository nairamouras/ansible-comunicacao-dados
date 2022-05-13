# :desktop_computer: ansible-comunicacao-dados
  Projeto da disciplina de Comunicação de Dados para instalação de softwares em múltiplos computadores através de um servidor utilizando o Ansible.

## Conteúdo

1. [Introdução](https://github.com/nairamouras/ansible-comunicacao-dados/blob/main/README.md#introdu%C3%A7%C3%A3o)
2. [O que é o Ansible?](https://github.com/nairamouras/ansible-comunicacao-dados/blob/main/README.md#o-que-%C3%A9-o-ansible)
3. [Ferramentas utilizadas](https://github.com/nairamouras/ansible-comunicacao-dados/blob/main/README.md#ferramentas-utilizadas)
5. [Etapa 1: configurando o Linux e o Ansible](https://github.com/nairamouras/ansible-comunicacao-dados/blob/main/README.md#etapa-1-configurando-o-servidor-linux-e-o-ansible)
6. [Etapa 2:]()
7. [Referências](https://github.com/nairamouras/ansible-comunicacao-dados/blob/main/README.md#refer%C3%AAncias)

## Introdução

  A ideia para este projeto foi delineada visando a otimização da configuração das máquinas dos laboratórios de informática do IFMT - Campus Octayde para o início das aulas das turmas anuais e semestrais. Para tanto, o objetivo é criar um servidor com uma máquina central e realizar a instalação de múltiplos programas simultâneamente em todos os computadores dos laboratórios.

## O que é o Ansible?

  O Ansible é uma ferramenta open source para automação de processos manuais de TI como instalação de softwares, provisionamento de infraestrutura, compartilhamento de automação e configurações através da mesma rede, etc.
  
## Ferramentas utilizadas

  - Para o servidor Linux:
    - Ansible;
    - Python3-pip;
    - WinRM

  - Para as máquinas Windows:
    - PowerShell;
    - Chocolatey;
    - WinRM

## Etapa 1: configurando o servidor Linux

  A primeira etapa a ser realizada é a instalação e configuração de uma máquina, física ou virtual, com o Sistema Operacional Linux para a função de servidor de rede do projeto.
  
  Caso seja utilizada uma máquina virtual, faça o download e instalação do [Virtual Box](https://www.virtualbox.org/wiki/Downloads) e siga as instruções deste [link](https://canaltech.com.br/software/como-criar-uma-maquina-virtual-com-o-virtualbox/).
  
  Em seguida,


## Etapa 2: configurando as máquinas dos laboratórios

  A segunda etapa consiste em configurar as máquinas dos laboratórios para realizar a conexão de rede com o servidor já criado.
  
  Para tanto, inicia-se realizando o download e instalação do [chocolatey](chocolatey.org/install) e do WinRM por meio do PowerShell usando o administrador da máquina.





## Referências

RED HAT. ***O que é o Ansible?*** Disponível em: <<https://www.redhat.com/pt-br/technologies/management/ansible/what-is-ansible>>

LINUX HELP. ***How to install an application on Windows by using Ansible playbook.*** Disponível em: <<https://www.linuxhelp.com/how-to-install-an-application-on-windows-by-using-ansible-playbook>>

ANSIBLE DOCUMENTATION. ***Setting up a Windows Host.*** Disponível em: <<https://docs.ansible.com/ansible/latest/user_guide/windows_setup.html>>


