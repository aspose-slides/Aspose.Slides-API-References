---
title: reorder method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ishapecollection/reorder/
weight: 370
---
## reorder(self, index, shape) {#int-ishape}
Flyttar den specificerade formen till en ny position inom formsamlingen.


```python
def reorder(self, index, shape):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Det nollbaserade målindexet där formen ska placeras. |
| shape | [`IShape`](/slides/python-net/sv/aspose.slides/ishape) | Det [`IShape`](/slides/python-net/sv/aspose.slides/ishape) att flytta inom samlingen. |


## reorder(self, index, shapes) {#int-listishape}
Flyttar de specificerade formerna inom formsamlingen, placerar dem med början på det angivna indexet.


```python
def reorder(self, index, shapes):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Det nollbaserade målindexet där den första specificerade formen ska placeras; <br/><br/>            efterföljande former följer i den angivna ordningen. |
| shapes | **List[IShape]** | En eller flera [`IShape`](/slides/python-net/sv/aspose.slides/ishape) instanser att flytta inom samlingen. |



### Se även
* klass [`IShape`](/slides/python-net/sv/aspose.slides/ishape)
* klass [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)