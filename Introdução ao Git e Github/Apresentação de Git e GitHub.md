#  GIT
    É um software pronto - 2005 ((open source))
    Um software de versão de código, ou seja é colaborativo. Ou seja, e algo para todos do mundo verem e monitora as versões do código como já dito.

#GitHub
    É da Microsoft ((pode ser pago))

##GIT ≠ GitHub

O GitHub

-Existe para controle de versão
-Armazenamento em nuvem (repositórios)
-Trabalho em Equipe (versionamento de código)
-Melhorar seu Código
-Reconhecimento (rede social, interação social)

###Comandos Básicos para um bom desempenho no terminal:

    GUI x CLI
GUI é graphic user interface
CLI é Command line interface

São feitos por linhas de comando

-mudar pastas
-listar pastas
-criar pastas/arquivos
-deletar pastas/arquivos

**No Windows**
-cd
-dir
-mkdir
-del/rm dir

**No Linux/ou Apple**
-cd
-ls
-mkdir
-rm-rf

dir - Listar
cd - change director
cd.. - para voltar
cls - para limpar ao prompt
tab - complpeta colocando a primeira letra
mkdir - cria a pasta
del - deletar apenas arquivos
rmdir - remover director ((todo repositório)) /s /q

###Tópicos Fundamentais para entender o funcionamento do GIT

-SHA1 - secure hash algoritmo ((criptografa as coisas)) que gera um conjunto de caracteres que são identificadores de 40 digitos únicos. Uma forma curta de representar o estado do arquivo.

###Objetios internos do GIT

-Blobs - metadados do git - echo - pega as strings e ela devolve o SHA1
-Trees - armazena os blobs - monta estrutura de onde estão localizados os arquivos
-Commits - junta tudo - tree, parente, autor, mensaagem, timestamp

É um sistema distribuído seguro, tem seu código hosteado na nuvem, representa o estado final do seu software.

##Chave SSH e senha token - GitHub

A chave SSH - conexão segura e encriptada entre duas máquinas (pública e privada)


##Primeiros Comandos com Git

Iniciando o Git e cirando um commit

-Iniciar o Git - git nit
-Iniciar o Versionamento - git add
-Criar um commit - git commit

##Ciclo de Vida
###Passo a Passo no Ciclo de Vida

-git nit - inicializa o repositório
-tracked - rastreados pelo git
    - unmodified - ainda não foi modificada
    - modified - foi modificada
    - staged
-untracked - não há ciência sobre eles

Exemplo:
-Add estava untracked
-Untracked foi direto pro staged
-Unmodified -> modifiica para modified
-Unmodified -> removido, vira untracked

No Staged ele tá se preparando para virar um commit

Servidor - remove repository
-Ambiente de desenvolvimento
-working directory
-staging area
-local repository - tem que estar commited

Git Status ((ver o status))
-git add *
-git add.
-git commit -m
