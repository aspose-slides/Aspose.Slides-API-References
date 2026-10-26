---
title: reorder method
second_title: Referencia de API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides/ishapecollection/reorder/
weight: 370
---
## reorder(self, index, shape) {#int-ishape}
Mueve la forma especificada a una nueva posición dentro de la colección de formas.

```python
def reorder(self, index, shape):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice de destino basado en cero donde se colocará la forma. |
| shape | [`IShape`](/slides/python-net/es/aspose.slides/ishape) | El [`IShape`](/slides/python-net/es/aspose.slides/ishape) que se moverá dentro de la colección. |

## reorder(self, index, shapes) {#int-listishape}
Mueve las formas especificadas dentro de la colección de formas, colocándolas a partir del índice proporcionado.

```python
def reorder(self, index, shapes):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice de destino basado en cero donde se colocará la primera forma especificada; <br/><br/>            las formas subsecuentes siguen en el orden proporcionado. |
| shapes | **List[IShape]** | Una o más instancias de [`IShape`](/slides/python-net/es/aspose.slides/ishape) para mover dentro de la colección. |

### Ver también
* clase [`IShape`](/slides/python-net/es/aspose.slides/ishape)
* clase [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)