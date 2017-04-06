# aulaGit

#### Criar o repositório com o comando _init_ (após entrar na pasta que será usada para o projeto)
`git init`
> Deverá ser feita as configurações de usuário e email

#### Configuração inicial do git. *nome e email*
```
git config --global user.name "<seu nome>"
git config --global user.email "<seu email>"
```


#### Visualizar a lista de arquivos
> após criar os arquivos na pasta do projeto ex: index.php, teste.txt, img1.png. Execute:

`git status`
> você poderá ver que esses arquivos estarão _untracked_, ou seja não estão sendo controlados pelo git


#### Adicionando o(s) arquivo(s) _untracked_ na lista de arquivos a serem comitados**

`git add . ` 
> Para adicionar na lista de _commit_ todos os arquivos que estão _untracked_

`git add <nome do arquivo>`
> Para adicionar na lista de _commit_ um arquivo específico da lista de arquivos _untracked_


#### Criando _commit_ e definindo a mensagem
`git commit -m "mensagem do commit"`
ou
`git commit` 
> Para abrir o editor de textos e permitirá escrever a mensagem do commit com quebras de linhas possibilitando detalhar melhor a mensagem sem deixar de criar uma mensagem simples e completa 


#### Enviando para o repositório central (GitHub)
`git push origin master`
> No caso de você não ter gerado a key ssh, será solicitado no prompt o seu login e senha para concluir o _push_


#### Criando uma nova _branch_
`git checkout -b <nome da branch`
> automaticamente o git trocará para a nova _branch_


#### Trocando de _branch_ e comitando
```
git checkout <nome da branch>
git add <nome do arquivo>
git commit -m "mensagem do commit"
git push origin <nome da branch>
```




