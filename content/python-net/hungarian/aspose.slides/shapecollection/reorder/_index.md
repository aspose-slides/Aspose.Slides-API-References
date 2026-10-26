---
title: reorder method
second_title: Aspose.Slides a Pythonhoz .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides/shapecollection/reorder/
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
| index | **int** | A nullától induló célindex, ahol az alakzat elhelyezésre kerül. |
| shape | [`IShape`](/slides/python-net/hu/aspose.slides/ishape) | A [`IShape`](/slides/python-net/hu/aspose.slides/ishape) amelyet a gyűjteményben kell áthelyezni. |

## reorder(self, index, shapes) {#int-listishape}
Áthelyezi a megadott alakzatokat a alakzatgyűjteményben, azokat a megadott indexnél kezdi elhelyezni.

```python
def reorder(self, index, shapes):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A nullától induló célindex, ahol az első meghatározott alakzat el lesz helyezve;<br/><br/>            a további alakzatok a megadott sorrendben követik. |
| shapes | **List[IShape]** | Egy vagy több [`IShape`](/slides/python-net/hu/aspose.slides/ishape) példány, amelyet a gyűjteményben kell áthelyezni. |

### Lásd még
* osztály [`IShape`](/slides/python-net/hu/aspose.slides/ishape)
* osztály [`ShapeCollection`](/slides/python-net/hu/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)