---
title: set_metered_key method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/metered/set_metered_key/
weight: 60
---
## set_metered_key(self, public_key, private_key) {#str-str}
Définit la clé publique et privée mesurée.
            Si vous achetez une licence mesurée, au démarrage de l'application, cette API doit être appelée, généralement cela suffit. 
            Cependant, si le téléchargement des données de consommation échoue constamment et dépasse 24 heures, la licence sera mise en statut d'évaluation, 
            pour éviter ce cas, vous devez vérifier régulièrement le statut de la licence ; si elle est en statut d'évaluation, appelez à nouveau cette API.


```python
def set_metered_key(self, public_key, private_key):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| public_key | **str** | public key |
| private_key | **str** | private key |



### Voir aussi
* classe [`Metered`](/slides/python-net/fr/aspose.slides/metered)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)