---
title: remove_node method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.smartart/ismartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
Entfernt Knoten oder Unterknoten nach Index.

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
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | index ist kleiner als 0. -oder- index ist gleich oder größer als die Anzahl der Geschwister. |

## remove_node(self, node_obj) {#ismartartnode}
Entfernt Knoten oder Unterknoten.

```python
def remove_node(self, node_obj):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| node_obj | [`ISmartArtNode`](/slides/python-net/de/aspose.slides.smartart/ismartartnode) | Zu entfernender Knoten. |

### Siehe auch
* Klasse [`ISmartArtNode`](/slides/python-net/de/aspose.slides.smartart/ismartartnode)
* Klasse [`ISmartArtNodeCollection`](/slides/python-net/de/aspose.slides.smartart/ismartartnodecollection)
* Modul [`aspose.slides.smartart`](/slides/python-net/de/aspose.slides.smartart)
* Bibliothek [`Aspose.Slides`](/slides/python-net)