# Criar uma Action JavaScript utilizando TypeScript.

:rocket: :rocket: :rocket:

Se você não sabe o que está fazendo acesse o link: [Hello World JavaScript Action](https://github.com/actions/hello-world-javascript-action)

## Criar ação a partir deste template

Clique em `Use this Template` e modifique com as informações para o seu repositório.

## Escreva seu código dentro do arquivo Main (Crie novos arquivos se necessário, mas sempre os chame dentro do Main)

> Primeiramente tenha a versão mais recente do node instalada em conjunto com o npm.

Instalar as dependências

```bash
$ npm install
```

Build typescript and package it for distribution

```bash
$ npm run build && npm run package
```

## Edite o action.yml

O action.yml define os inputs e outputs de sua Action.

documentação da sintaxe de um action.yml [documentation](https://help.github.com/en/articles/metadata-syntax-for-github-actions)

## Buildando e subindo para repositório para utilizar a Action

```bash
$ npm run all
$ git add -A
$ git commit -a -m "prod dependencies"
$ git push
$ git tag -a -m "prod dependencies" v1.0
$ git push --follow-tags
```

:rocket: :rocket: :rocket:
