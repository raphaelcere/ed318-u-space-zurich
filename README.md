# ED-318 – DAR Zurich

Exemple de zone géographique UAS au format **EUROCAE ED-318** (GeoJSON `Feature`) : la zone `DARZRH` (DAR Zurich), de type `PROHIBITED`, publiée par Skyguide.

## Consulter la géométrie

- [Ouvrir dans geojson.io](https://geojson.io/#data=data:application/json,%7B%22type%22%3A%22Feature%22%2C%22id%22%3A%22a5953add-02fe-4029-a079-78a45863a054%22%2C%22properties%22%3A%7B%22identifier%22%3A%22DARZRH%22%2C%22country%22%3A%22CHE%22%2C%22name%22%3A%5B%7B%22lang%22%3A%22en-GB%22%2C%22text%22%3A%22DAR%20Zurich%22%7D%5D%2C%22type%22%3A%22PROHIBITED%22%2C%22variant%22%3A%22COMMON%22%2C%22region%22%3A0%2C%22reason%22%3A%5B%22DAR%22%5D%2C%22message%22%3A%5B%7B%22lang%22%3A%22de-CH%22%2C%22text%22%3A%22Der%20Betrieb%20von%20unbemannten%20Luftfahrzeugen%20ist%20verboten%22%7D%2C%7B%22lang%22%3A%22fr-CH%22%2C%22text%22%3A%22L%27exploitation%20d%27a%C3%A9ronefs%20sans%20occupants%20est%20interdite%22%7D%2C%7B%22lang%22%3A%22it-CH%22%2C%22text%22%3A%22L%27esercizio%20di%20aeromobili%20senza%20occupanti%20%C3%A8%20vietato%22%7D%2C%7B%22lang%22%3A%22en-GB%22%2C%22text%22%3A%22The%20operation%20of%20unmanned%20aircraft%20is%20prohibited%22%7D%5D%2C%22zoneAuthority%22%3A%5B%7B%22name%22%3A%5B%7B%22lang%22%3A%22en-GB%22%2C%22text%22%3A%22Skyguide%22%7D%5D%2C%22service%22%3A%5B%7B%22lang%22%3A%22en-GB%22%2C%22text%22%3A%22Skyguide%20Special%20Flight%20Office%22%7D%5D%2C%22siteURL%22%3A%22https%3A%2F%2Fskyguide.ch%2Fservices%2Fspecial-flights%22%2C%22purpose%22%3A%22AUTHORIZATION%22%7D%5D%2C%22limitedApplicability%22%3A%5B%7B%22startDateTime%22%3A%222025-10-02T00%3A00%3A00Z%22%2C%22endDateTime%22%3A%222036-09-28T10%3A15%3A53.86752172%2B02%3A00%22%7D%5D%2C%22dataSource%22%3A%7B%22creationDate%22%3A%222012-10-18T00%3A00%3A00Z%22%2C%22updateDateTime%22%3A%222012-10-18T00%3A00%3A00Z%22%2C%22originator%22%3A%7B%22lang%22%3A%22en-GB%22%2C%22text%22%3A%22Skyguide%22%7D%7D%2C%22extendedProperties%22%3A%7B%22active%22%3Afalse%2C%22addInfoText%22%3A%5B%7B%22lang%22%3A%22de-CH%22%2C%22text%22%3A%22Ausnahmebewilligungen%20k%C3%B6nnen%20bei%20der%20zust%C3%A4ndigen%20Stelle%20beantragt%20werden.%22%7D%2C%7B%22lang%22%3A%22fr-CH%22%2C%22text%22%3A%22Des%20autorisations%20exceptionnelles%20peuvent%20%C3%AAtre%20demand%C3%A9es%20aupr%C3%A8s%20de%20l%27autorit%C3%A9%20comp%C3%A9tente.%22%7D%2C%7B%22lang%22%3A%22it-CH%22%2C%22text%22%3A%22I%20permessi%20d%27esenzione%20possono%20essere%20richiesti%20all%27autorit%C3%A0%20competente.%22%7D%2C%7B%22lang%22%3A%22en-GB%22%2C%22text%22%3A%22Exemption%20permits%20may%20be%20applied%20for%20at%20the%20competent%20authority.%22%7D%5D%2C%22dynamic%22%3Atrue%7D%7D%2C%22geometry%22%3A%7B%22type%22%3A%22Polygon%22%2C%22coordinates%22%3A%5B%5B%5B8.345179438411252%2C47.387373562244385%5D%2C%5B8.336985683390006%2C47.45130006405109%5D%2C%5B8.464991262346754%2C47.453383477842905%5D%2C%5B8.5719206439519%2C47.39931459382704%5D%2C%5B8.579778819155292%2C47.364156036215405%5D%2C%5B8.396438302689985%2C47.36537225719862%5D%2C%5B8.345179438411252%2C47.387373562244385%5D%5D%5D%2C%22layer%22%3A%7B%22upper%22%3A393.7008%2C%22upperReference%22%3A%22AGL%22%2C%22lower%22%3A0%2C%22lowerReference%22%3A%22AGL%22%2C%22uom%22%3A%22ft%22%7D%7D%7D) (le contenu du fichier est embarqué dans le lien, il fonctionne sans dépendre de l'hébergement du dépôt).
- Variante pointant directement le fichier du dépôt (à activer une fois le dépôt publié, en remplaçant `<OWNER>` et `<REPO>`) :
  `https://geojson.io/#id=github:<OWNER>/<REPO>/blob/main/data/dar-zurich.json`

> geojson.io affiche la géométrie et les propriétés (panneau « JSON »). La limite verticale (`layer`) et les autres attributs ED-318 ne sont pas interprétés par l'outil : ils restent visibles, mais seule la 2D est représentée.

## Contenu du dépôt

| Fichier | Description |
|---|---|
| `data/dar-zurich.json` | Zone `DARZRH` au format ED-318 (GeoJSON `Feature`, `Polygon`) |

## Résumé de la zone

| Champ | Valeur |
|---|---|
| Identifiant | `DARZRH` |
| Pays | `CHE` |
| Type / variante | `PROHIBITED` / `COMMON` |
| Motif | `DAR` |
| Limites verticales | 0 – 393.7008 ft AGL |
| Autorité | Skyguide (Special Flight Office) |
| Applicabilité | du 2025-10-02 au 2036-09-28 |
| Langues des messages | de-CH, fr-CH, it-CH, en-GB |

## Validation rapide

```bash
python3 -c "import json; d=json.load(open('data/dar-zurich.json', encoding='utf-8')); r=d['geometry']['coordinates'][0]; assert r[0]==r[-1]; print('OK')"
```
