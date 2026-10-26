---
title: set_embedded_data method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/ioleobjectframe/set_embedded_data/
weight: 50
---
## set_embedded_data(self, embedded_data) {#ioleembeddeddatainfo}
Définit les informations sur les données OLE incorporées.


```python
def set_embedded_data(self, embedded_data):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| embedded_data | [`IOleEmbeddedDataInfo`](/slides/python-net/fr/aspose.slides/ioleembeddeddatainfo) | Données incorporées [`IOleEmbeddedDataInfo`](/slides/python-net/fr/aspose.slides/ioleembeddeddatainfo) |

### Remarques

Cette méthode modifie les propriétés de l'objet pour refléter les nouvelles données et définit le drapeau IsObjectLink sur false, indiquant que l'objet OLE est incorporé.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Lorsque le paramètre embeddedData est None. |



### Voir aussi
* classe [`IOleEmbeddedDataInfo`](/slides/python-net/fr/aspose.slides/ioleembeddeddatainfo)
* classe [`IOleObjectFrame`](/slides/python-net/fr/aspose.slides/ioleobjectframe)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)