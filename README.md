# meu projeto

git init
 -iniciar novo projeto com git

 git add <nome-arquivo>
 - add os arquivos que estão prontos para serem comitados

 git commit -m "mensagem commit"
 - comiite os arquivos no historico

 git log
 - mostra os ultimos commits, log de alterações

 git status
 - como esta o estado da nossa ramificação

 git diff
 - mostra o que foi alterado
 - o que tem de alteração na ramificação

 git merge
 - mescla ramificações

 git branch
 - mostra a branch atual

 git branch -b <nome-branch>
 - cria uma nova branch a partir do historico da branch atual

 git checkout <nome-branch>
 - muda para essa branch

  git checkout -b <nome-branch>
  - criar uma nova branch a partir da branch atual que estamos

  git remote add <nome> <url>
  - add um novo repositorio remoto

  git push <nome> <nome_branch>
  - manda nossas alterações locais para o repositorio remoto, para cada branch

  git pull <nome> <nome_branch>
  - pega as alterações do repositorio remoto e joga para nossa maquina

  git fetch
  - atualiza o nosso historico local de acordo com o historico salvo no repositorio