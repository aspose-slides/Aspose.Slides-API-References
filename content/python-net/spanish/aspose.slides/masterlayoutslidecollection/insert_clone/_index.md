---
title: insert_clone method
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/masterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
Inserta una copia de una diapositiva de diseño especificada en la posición especificada de la colección.

### Devuelve

Diapositiva insertada.



```python
def insert_clone(self, index, source_layout):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | Índice de la nueva diapositiva. |
| source_layout | [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide) | Diapositiva a clonar. |

### Observaciones

El nuevo diseño estará vinculado con la diapositiva maestra principal para esta colección de diapositivas de diseño. Por lo tanto, esto es análogo a copiar/pegar con la opción "Use Destination Theme" en PowerPoint.



### Ver también
* clase [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide)
* clase [`MasterLayoutSlideCollection`](/slides/python-net/es/aspose.slides/masterlayoutslidecollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)