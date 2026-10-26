---
title: reorder method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ishapecollection/reorder/
weight: 370
---
## reorder(self, index, shape) {#int-ishape}
Verschiebt die angegebene shape an eine neue Position innerhalb der shape Sammlung.

```python
def reorder(self, index, shape):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Der nullbasierte Zielindex, an dem die shape platziert wird. |
| shape | [`IShape`](/slides/python-net/de/aspose.slides/ishape) | Das [`IShape`](/slides/python-net/de/aspose.slides/ishape) zum Verschieben innerhalb der Sammlung. |

## reorder(self, index, shapes) {#int-listishape}
Verschiebt die angegebenen shapes innerhalb der shape Sammlung und platziert sie ab dem angegebenen Index.

```python
def reorder(self, index, shapes):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Der nullbasierte Zielindex, an dem die erste angegebene shape platziert wird;<br/><br/>nachfolgende shapes werden in der angegebenen Reihenfolge platziert. |
| shapes | **List[IShape]** | Ein oder mehrere [`IShape`](/slides/python-net/de/aspose.slides/ishape)-Instanzen zum Verschieben innerhalb der Sammlung. |

### Siehe auch
* Klasse [`IShape`](/slides/python-net/de/aspose.slides/ishape)
* Klasse [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)