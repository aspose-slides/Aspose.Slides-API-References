---
title: remove_node method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.smartart/ismartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
Verwijder knoop of subknoop op index.


```python
def remove_node(self, index):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | Nulgebaseerde index van knoop |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | index is kleiner dan 0.  -of- index is gelijk aan of groter dan het aantal siblings. |


## remove_node(self, node_obj) {#ismartartnode}
Verwijder knoop of subknoop.


```python
def remove_node(self, node_obj):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| node_obj | [`ISmartArtNode`](/slides/python-net/nl/aspose.slides.smartart/ismartartnode) | Knoop om te verwijderen. |



### Zie ook
* klasse [`ISmartArtNode`](/slides/python-net/nl/aspose.slides.smartart/ismartartnode)
* klasse [`ISmartArtNodeCollection`](/slides/python-net/nl/aspose.slides.smartart/ismartartnodecollection)
* module [`aspose.slides.smartart`](/slides/python-net/nl/aspose.slides.smartart)
* bibliotheek [`Aspose.Slides`](/slides/python-net)