# git-academy2022

## Inicialização de um projeto

```bash
git init
```

## Configurações iniciais

```bash
git config --global user.name "Raul"
git config --global user.email "rauloliveirasabin15@gmail.com"
```

## Controle de alterações

para visualizar as alterações feitas vamos utilizar:

```bash
git status
```

## Criando commits

Primeiramente precisamos adicionar as mudanças e enfim 'comitar':
> Utilize o ponto para adicionar todas as alterações do projeto.
```bash
git add .
git commit -m "Descricao das alterações"
```
## Branches

Podemos ramificar o código usando branches, para criar uma nova, executamos:

```bash
git switch --create <nome-da-nova-branch>
# or
git checkout -b <nome-da-nova-branch>
```

- Listando branches criadas:

```bash
git branch
```

- Apagando branch

```bash
git branch -D <nome-da-branch>
```

## GitHub

- Adicionando um remote origin:
```bash
git remote add origin https://github.com/user/repo-name.git
```

- Subindo alterações:
```bash
git push origin <nome-da-branch>
# caso a branch nao exista no GitHub use:
git push -u origin <nome-da-branch>
```

