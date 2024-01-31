# Projeto introdutório trilha (K1-T1): Versionamento de Código

## Primeira atividade da trilha

_O Git suporta rápidas criações de ramos (branches) e mesclas (merges), e inclui ferramentas específicas para visualização e navegação de históricos de desenvolvimento não lineares. Uma suposição intrínseca no Git é que uma mudança será mesclada mais do que é escrita, enquanto é passada por vários revisores._


Abaixo estão alguns comandos git:


- `git init`: inicializar um repositório **local** vazio
- `git add nomeArquivo.formato`: adicionar um arquivo para a Stage Area, os arquivos nesse local serão vinculados ao próximo commit
- `git commit -m "mensagem aqui"`: mover os arquivos da stage área para o repositório local
- `git pull`: buscar e trazer mudanças do repositório **remoto** para o seu repositório **local** 
- `git push`: enviar o arquivo do repositório local para o repositóro remoto.
- `git merge outrabranchaqui`: mesclar branches na Branch atual
- `git log`: histórico de commits ou um específico
- `git clone linkDoRepositório`: clonar um repositório


Exemplo:
```sh
git clone https://github.com/charles/Python-curso
```

É possível obter mais informações clicando [aqui](https://git-scm.com/docs/git/pt_BR).


