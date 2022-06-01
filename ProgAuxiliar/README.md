## Códigos Basicos
*O arquivo da lista tem que ser m3u com o seguinte padrão:*
```
#EXTM3U

#EXTINF:-1 ,Nome aqui
Link aqui, logo abaixo
```
*Exemplo:*
```
#EXTM3U

#EXTINF:-1 ,Scream
https://onedrive.live.com/download?resid=67CBD9EC082C79C5!927&authkey=%21AO9og
```
## Funções

Há alguns complementos, que são totalmente opcionais, com utilidades variadas e individuais.

###### Description
*Guarda uma descrição*

###### Group Title
*Cria uma tag e classifica o objeto. Uma ótima opção para organizar sua lista em determinadas categorias específicas.*

###### Tvg Logo
*Armazena uma url de arquivo imagem, geralmente usado para atribuir capas, icones e logos.*

###### Type
*Classifica em um de três tipos prédefinidos.* 

```"stream"``` *Esse é o valor padrão do 'type'. Funciona sem as funções de tempo, todo a transmição é continua.*

```"video"``` *Permite que a transmissão tenha as funções temporais, como pausar, pular, retroceder, contabilizar.*

```"playlist"``` *Serve para redirecionar para outra lista, crianda a sensação de pastas.*

##  Uma lista com alguns itens usando funções:
```
#EXTM3U

#EXTINF:-1 type="video" group-title="Slasher('Terror')" ,Scream (1996)
https://onedrive.live.com/download?resid=67CBD9EC082C79C5!927&authkey=%21AO9og

#EXTINF:-1 type="video" group-title="Slasher('Terror')" ,Scream 2 (1997)
https://onedrive.live.com/download?resid=67CBD9EC082C79C5!928&authkey=%21AGe0jQL9DColb7E

#EXTINF:-1 type="video" group-title="Slasher('Terror')" ,Scream 3 (2000)
https://onedrive.live.com/download?resid=67CBD9EC082C79C5!930&authkey=%21AHmR%2DBzWogvhVKk
```
