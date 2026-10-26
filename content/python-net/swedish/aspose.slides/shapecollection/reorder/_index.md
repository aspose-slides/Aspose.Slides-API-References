---
title: reorder method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/shapecollection/reorder/
weight: 370
---
## reorder(self, index, shape) {#int-ishape}
Flyttar den angivna formen till en ny position i formsamlingen.


```python
def reorder(self, index, shape):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Det nollbaserade målindexet där formen kommer att placeras. |
| shape | [`IShape`](/slides/python-net/sv/aspose.slides/ishape) | Den [`IShape`](/slides/python-net/sv/aspose.slides/ishape) som ska flyttas inom samlingen. |


## reorder(self, index, shapes) {#int-listishape}
Flyttar de angivna formerna inom formsamlingen och placerar dem med början vid det angivna indexet.


```python
def reorder(self, index, shapes):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Det nollbaserade målindexet där den första angivna formen kommer att placeras; efterföljande former placeras i den angivna ordningen. |
| shapes | **List[IShape]** | Ett eller flera [`IShape`](/slides/python-net/sv/aspose.slides/ishape)-instanser att flytta inom samlingen. |



### See Also
* klass [`IShape`](/slides/python-net/sv/aspose.slides/ishape)
* klass [`ShapeCollection`](/slides/python-net/sv/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)