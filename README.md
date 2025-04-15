# Loja Virtual da turma 2TSCPV
Criar um diretório. Por exemplo: 
mkdir C:\dev\fiap\lojavirtual2

Entrar no diretório. 
cd C:\dev\fiap\lojavirtual2

Inicializar o repositório GIT nesse diretório
`git init`

Descompactar os arquivos lojavirtual.zip dentro desse diretório

Adicionar os todos os novos arquivos ao repositório local
git add .

Efetivar (commit) das atualizações/remoções/inserções realizadas
git commit -m 'mensagem'

Definir a branch que esta sendo utilizada
git branch -M main

Configurar o repositório remoto onde serão amrazenados os arquivos e alterações do repositório local
git remote add origin https://github.com/rksakai/lojavirtual.git

Enviar os arquivos modificados no repositório local para o repositório remoto
git push -u origin main
