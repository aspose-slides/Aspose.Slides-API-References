---
title: remove_node method
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.smartart/smartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
Eliminar nodo o subnodo por índice


```python
def remove_node(self, index):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | Índice basado en cero del nodo |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | el índice es menor que 0. -or- el índice es igual o mayor que la cantidad de hermanos |


## remove_node(self, node) {#ismartartnode}
Eliminar nodo o subnodo


```python
def remove_node(self, node):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| node | [`ISmartArtNode`](/slides/python-net/es/aspose.slides.smartart/ismartartnode) | Nodo a eliminar |



### Ver también
* clase [`ISmartArtNode`](/slides/python-net/es/aspose.slides.smartart/ismartartnode)
* clase [`SmartArtNodeCollection`](/slides/python-net/es/aspose.slides.smartart/smartartnodecollection)
* módulo [`aspose.slides.smartart`](/slides/python-net/es/aspose.slides.smartart)
* biblioteca [`Aspose.Slides`](/slides/python-net)