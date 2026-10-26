---
title: remove_node method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.smartart/smartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
Verwijder knoop of subknoop op index


```python
def remove_node(self, index):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | Nulgebaseerde index van knoop |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | index is kleiner dan 0.  -of- index is gelijk aan of groter dan het aantal broers |

## remove_node(self, node) {#ismartartnode}
Verwijder knoop of subknoop


```python
def remove_node(self, node):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| node | [`ISmartArtNode`](/slides/python-net/nl/aspose.slides.smartart/ismartartnode) | Knoop om te verwijderen |


### Zie ook
* klasse [`ISmartArtNode`](/slides/python-net/nl/aspose.slides.smartart/ismartartnode)
* klasse [`SmartArtNodeCollection`](/slides/python-net/nl/aspose.slides.smartart/smartartnodecollection)
* module [`aspose.slides.smartart`](/slides/python-net/nl/aspose.slides.smartart)
* library [`Aspose.Slides`](/slides/python-net)