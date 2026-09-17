---
title: add_from_html method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/iparagraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
Ajoute du texte à partir d’une chaîne html spécifiée à la collection.


```python
def add_from_html(self, text):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| text | **str** | Texte HTML. |


## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Ajoute du texte à partir d’une chaîne html spécifiée à la collection.


```python
def add_from_html(self, text, resolver, uri):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| text | **str** | Texte HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/fr/aspose.slides.importing/iexternalresourceresolver) | Objet de rappel du résolveur qui résout les URI et récupère les objets référencés. |
| uri | **str** | URI pour ajouter le document HTML. Utilisé pour résoudre les liens relatifs. |

### Remarques

Spécifier le résolveur peut potentiellement introduire une vulnérabilité. Utilisez-le avec précaution.



### Voir aussi
* classe [`IExternalResourceResolver`](/slides/python-net/fr/aspose.slides.importing/iexternalresourceresolver)
* classe [`IParagraphCollection`](/slides/python-net/fr/aspose.slides/iparagraphcollection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)