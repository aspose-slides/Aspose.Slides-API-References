---
title: reorder method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ishapecollection/reorder/
weight: 370
---
## reorder(self, index, shape) {#int-ishape}
Přesune zadaný tvar na novou pozici v kolekci tvarů.


```python
def reorder(self, index, shape):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Nulový index cíle, kde bude tvar umístěn. |
| shape | [`IShape`](/slides/python-net/cs/aspose.slides/ishape) | [`IShape`](/slides/python-net/cs/aspose.slides/ishape) k přesunutí v kolekci. |


## reorder(self, index, shapes) {#int-listishape}
Přesune zadané tvary v kolekci tvarů, umístí je počínaje daným indexem.


```python
def reorder(self, index, shapes):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Nulový index cíle, kde bude umístěn první určený tvar; <br/><br/>            následné tvary jsou umístěny v pořadí, v jakém jsou uvedeny. |
| shapes | **List[IShape]** | Jedna nebo více instancí [`IShape`](/slides/python-net/cs/aspose.slides/ishape) k přesunutí v kolekci. |



### Viz také
* třída [`IShape`](/slides/python-net/cs/aspose.slides/ishape)
* třída [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)