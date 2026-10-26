---
title: remove_node method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.smartart/smartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
Entfernt Knoten oder Unterknoten nach Index


```python
def remove_node(self, index):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Nullbasierter Index des Knotens |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | index ist kleiner als 0.  -oder- index ist gleich oder größer als die Anzahl der Geschwister |


## remove_node(self, node) {#ismartartnode}
Entfernt Knoten oder Unterknoten


```python
def remove_node(self, node):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| node | [`ISmartArtNode`](/slides/python-net/de/aspose.slides.smartart/ismartartnode) | Knoten zum Entfernen |



### Siehe auch
* Klasse [`ISmartArtNode`](/slides/python-net/de/aspose.slides.smartart/ismartartnode)
* Klasse [`SmartArtNodeCollection`](/slides/python-net/de/aspose.slides.smartart/smartartnodecollection)
* Modul [`aspose.slides.smartart`](/slides/python-net/de/aspose.slides.smartart)
* Bibliothek [`Aspose.Slides`](/slides/python-net)