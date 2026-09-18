---
title: reorder method
second_title: Aspose.Slides Pythonhoz a .NET API-n keresztül
description: 
type: docs
url: /hu/aspose.slides/ishapecollection/reorder/
weight: 370
---
## reorder(self, index, shape) {#int-ishape}
Áthelyezi a megadott alakzatot a alakzatgyűjteményen belül egy új pozícióba.


```python
def reorder(self, index, shape):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A nulla-alapú célindex, ahol az alakzat el lesz helyezve. |
| shape | [`IShape`](/slides/python-net/hu/aspose.slides/ishape) | A [`IShape`](/slides/python-net/hu/aspose.slides/ishape) a gyűjteményen belül mozgatandó. |


## reorder(self, index, shapes) {#int-listishape}
Áthelyezi a megadott alakzatokat a alakzatgyűjteményen belül, úgy, hogy a megadott indexnél kezdődően helyezi el őket.


```python
def reorder(self, index, shapes):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A nulla-alapú célindex, ahol az első megadott alakzat el lesz helyezve; <br/><br/>            a további alakzatok a megadott sorrendben követik. |
| shapes | **List[IShape]** | Egy vagy több [`IShape`](/slides/python-net/hu/aspose.slides/ishape) példány mozgatásra a gyűjteményen belül. |



### Lásd még
* osztály [`IShape`](/slides/python-net/hu/aspose.slides/ishape)
* osztály [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)