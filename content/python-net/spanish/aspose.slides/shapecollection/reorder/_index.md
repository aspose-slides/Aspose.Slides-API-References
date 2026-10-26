---
title: reorder method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/shapecollection/reorder/
weight: 370
---
## reorder(self, index, shape) {#int-ishape}
Mueve la shape especificada a una nueva posición dentro de la colección de shapes.


```python
def reorder(self, index, shape):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice de destino basado en cero donde se colocará la shape. |
| shape | [`IShape`](/slides/python-net/es/aspose.slides/ishape) | El [`IShape`](/slides/python-net/es/aspose.slides/ishape) a mover dentro de la colección. |


## reorder(self, index, shapes) {#int-listishape}
Mueve los shapes especificados dentro de la colección de shapes, colocándolos a partir del índice dado.


```python
def reorder(self, index, shapes):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice de destino basado en cero donde se colocará la primera shape especificada; <br/><br/>            los shapes posteriores siguen en el orden proporcionado. |
| shapes | **List[IShape]** | Una o más instancias de [`IShape`](/slides/python-net/es/aspose.slides/ishape) para mover dentro de la colección. |



### Ver también
* clase [`IShape`](/slides/python-net/es/aspose.slides/ishape)
* clase [`ShapeCollection`](/slides/python-net/es/aspose.slides/shapecollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)