# Principais Comandos Git/GitHub

###Setar usuário
 - git config --global user.name "Rafael Souza"

###Setar email
 - git config --global user.email leonardo@software-ltda.com.br

###Listar configurações
 - git config --list

##Repositório Local

###Criar novo repositório
 - git init

###Verificar estado dos arquivos/diretórios
 - git status

###Adicionar um arquivo em específico
 - git add meu_arquivo.txt

###Adicionar um diretório em específico
 - git add meu_diretorio

###Adicionar todos os arquivos/diretórios
 - git add .

##Comitar arquivo/diretório

###Comitar um arquivo
 - git commit meu_arquivo.txt

###Comitar vários arquivos
 - git commit meu_arquivo.txt meu_outro_arquivo.txt

###Comitar informando mensagem
 - git commit meuarquivo.txt -m "minha mensagem de commit"

##Enviar arquivos/diretórios para o repositório remoto

###O primeiro push de um repositório deve conter o nome do repositório remoto e o branch.
 - git push -u origin master

###Os demais pushes não precisam dessa informação
 - git push

###Clonar um repositório remoto já existente
 - git clone git@github.com:leocomelli/curso-git.git