---
title: reorder method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/shapecollection/reorder/
weight: 370
---
## reorder(self, index, shape) {#int-ishape}
Verschiebt die angegebene Form an eine neue Position innerhalb der Formsammlung.


```python
def reorder(self, index, shape):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Der nullbasierte Zielindex, an dem die Form platziert wird. |
| shape | [`IShape`](/slides/python-net/de/aspose.slides/ishape) | Der [`IShape`](/slides/python-net/de/aspose.slides/ishape), der innerhalb der Sammlung verschoben wird. |


## reorder(self, index, shapes) {#int-listishape}
Verschiebt die angegebenen Formen innerhalb der Formsammlung und platziert sie beginnend ab dem angegebenen Index.


```python
def reorder(self, index, shapes):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Der nullbasierte Zielindex, an dem die erste angegebene Form platziert wird; <br/><br/>            nachfolgende Formen folgen in der angegebenen Reihenfolge. |
| shapes | **List[IShape]** | Ein oder mehrere [`IShape`](/slides/python-net/de/aspose.slides/ishape)-Instanzen zum Verschieben innerhalb der Sammlung. |



### Siehe auch
* Klasse [`IShape`](/slides/python-net/de/aspose.slides/ishape)
* Klasse [`ShapeCollection`](/slides/python-net/de/aspose.slides/shapecollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)