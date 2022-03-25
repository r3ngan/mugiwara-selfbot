# mugiwara-selfbot
## comment configurer le selfbot ?

> 1 - Récuperez votre token : https://www.youtube.com/watch?v=fv-H68OwsIA Vous pouvez regarder cette vidéo qui explique comment le récuperer
>
> 2 - Ensuite mettez votre token dans le config.js,
> exemple:
```json
"token":  "NzI5NjQ5NjE3OTQzMzk2Mzcy.XwMBjw.nTbuP7qa3zAdNUtVcpASy1nfoqE",
```
> 3 - Faites de même pour le prefix, votre lien twitch, le nsfw, le nitro auto claimer et le multi stream.
> ça doit vous ressembler à ça:
```js

const token = "NzI5NjQ5NjE3OTQzMzk2Mzcy.XwMBjw.nTbuP7qa3zAdNUtVcpASy1nfoqE"; //tu met ton token entre les guillemets
const prefix = "."; //tu met ton prefix entre les guillemets
const twitch = "https://twitch.tv/002_sans"; //tu met ton lien twitch ici 
const nsfw = "off"; //tu met on ou off (on pour activer le nsfw et off pour le désactiver)
const nitro_claimer = "on"; //tu met on ou off (on pour activer l'auto claimer et off pour le désactiver)
const multi_status = ["Votre multi stream 1 ",  "Votre multi stream 2 ",  "Votre multi stream 3 "]; //tu met le text que tu veut avoir en multi stream tu peut en mettre plus que 3 stv mais il faut bien mettre une virgule 
const premium = "premiumfree" //Mettez votre clée premium ici pas obligé
```
