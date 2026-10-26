---
title: add method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/captionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
Ajoute les sous-titres fermés WebVTT à la fin de la collection.

### Renvoie

L’instance [`ICaptions`](/slides/python-net/fr/aspose.slides/icaptions) ajoutée.



```python
def add(self, label, file_path):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| label | **str** | Le libellé des sous-titres fermés. |
| file_path | **str** | Le chemin du fichier WebVTT. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Lancé si `file_path` est `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Lancé si `file_path` est vide. |


## add(self, label, stream) {#str-iorawiobase}
Ajoute les sous-titres fermés WebVTT à la fin de la collection à partir d’un flux.

### Renvoie

L’instance [`ICaptions`](/slides/python-net/fr/aspose.slides/icaptions) ajoutée.



```python
def add(self, label, stream):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| label | **str** | Le libellé des sous-titres fermés. |
| stream | **io.RawIOBase** | Le flux d’entrée contenant des données au format WebVTT. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Lancé si `stream` est `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Lancé si les données d’entrée ne sont pas au format WebVTT. |



### Voir également
* classe [`CaptionsCollection`](/slides/python-net/fr/aspose.slides/captionscollection)
* classe [`ICaptions`](/slides/python-net/fr/aspose.slides/icaptions)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)