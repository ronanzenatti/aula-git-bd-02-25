# Comandos Git
Neste arquivo será apresentado os comandos git para uso futuro.

## No primeiro uso em um computador
Para que o GIT avise e saiba quem fez as alterações é necessário
configurar o usuário nas configurações globais do git.
```bash
git config --global user.name "Ronan Adriel Zenatti"

git config --global user.email "ronan.zenatti@fatec.sp.gov.br"
```

## Comandos para gestão do git
Para inicializar uma pasta como repositório git usamos o comando init.
Só utilizamos este comando 1 vez.
```bash
git init
```
Para ver a situação do repositório utilizamos o comando status.
Ele pode ser executado a qualquer momento para saber a situação da pasta.
Se estiver vermelho precisa adicionar os arquivo, se estiver verde estão prontos 
para salvar (commit).
Se não aparecer nada, ou o arquivo não está salvo ou já está tudo ok.
```bash
git status
```

Para adicionar todos os arquivos modificados para serem versionados utilizamos o add
**IMPORTANTE:** Tem que ser executado sempre que no status houver arquivos em vermelho
```bash
git add .
```

Para criar uma versão de tudo que foi modificado até aquele momento utilizamos o commit. <br>
**IMPORTANTE:** no -m temos que colocar uma mensagem do porque estamos salvando.
```bash
git commit -m "Porque estou salvando estas alterações"
```

Git push envia os commits do pc para o Github
```bash
git push
```


PULL baixa todas as atualizações que o repositório tem no Github e não está no seu pc.
```bash
git pull
```
