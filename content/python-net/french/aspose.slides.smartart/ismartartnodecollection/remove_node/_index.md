---
title: remove_node method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.smartart/ismartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
Supprime le nœud ou le sous-nœud par indice.


```python
def remove_node(self, index):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | Indice à base zéro du nœud |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | l'indice est inférieur à 0. -ou- l'indice est égal ou supérieur au nombre de frères. |


## remove_node(self, node_obj) {#ismartartnode}
Supprime le nœud ou le sous-nœud.


```python
def remove_node(self, node_obj):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| node_obj | [`ISmartArtNode`](/slides/python-net/fr/aspose.slides.smartart/ismartartnode) | Nœud à supprimer. |



### Voir aussi
* classe [`ISmartArtNode`](/slides/python-net/fr/aspose.slides.smartart/ismartartnode)
* classe [`ISmartArtNodeCollection`](/slides/python-net/fr/aspose.slides.smartart/ismartartnodecollection)
* module [`aspose.slides.smartart`](/slides/python-net/fr/aspose.slides.smartart)
* bibliothèque [`Aspose.Slides`](/slides/python-net)