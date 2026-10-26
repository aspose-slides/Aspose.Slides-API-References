---
title: insert_clone method
second_title: Aspose.Slides para Python mediante .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides/imasterlayoutslidecollection/insert_clone/
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
El nuevo diseño se vinculará con la diapositiva maestra principal de esta colección de diapositivas de diseño.
            Por lo tanto, esto es análogo a copiar/pegar con la opción "Usar tema de destino" en PowerPoint.

### Ver también
* clase [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide)
* clase [`IMasterLayoutSlideCollection`](/slides/python-net/es/aspose.slides/imasterlayoutslidecollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)