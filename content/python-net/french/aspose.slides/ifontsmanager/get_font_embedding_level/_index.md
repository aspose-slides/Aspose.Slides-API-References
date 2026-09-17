---
title: get_font_embedding_level method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/ifontsmanager/get_font_embedding_level/
weight: 40
---
## get_font_embedding_level(self, font_bytes, font_name) {#bytes-str}
Détermine le niveau d'intégration d'une police à partir du tableau d'octets donné et du nom de la police.

### Renvoie

Le niveau d'intégration de la police spécifiée.



```python
def get_font_embedding_level(self, font_bytes, font_name):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| font_bytes | **bytes** | Le tableau d'octets contenant les données de la police. |
| font_name | **str** | Le nom de la police. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Lancée lorsque `font_bytes` est None. |



### Voir aussi
* énumération [`EmbeddingLevel`](/slides/python-net/fr/aspose.slides/embeddinglevel)
* classe [`IFontsManager`](/slides/python-net/fr/aspose.slides/ifontsmanager)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)