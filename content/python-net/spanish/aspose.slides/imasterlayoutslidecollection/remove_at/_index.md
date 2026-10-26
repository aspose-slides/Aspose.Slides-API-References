---
title: remove_at method
second_title: Referencia de la API Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/imasterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
Elimina el elemento en el índice especificado de la colección.

```python
def remove_at(self, index):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice basado en cero del elemento a eliminar. |

### Observaciones

1) Para evitar lanzar la PptxEditException, compruebe la propiedad HasDependingSlides del diseño antes.
2) También puede usar el método [`ILayoutSlide.remove`](/slides/python-net/es/aspose.slides/ilayoutslide/remove) para simplificar el código.

### Excepciones

| Excepción | Descripción |
| :- | :- |
| [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception) | Se lanza si el diseño se usa en la presentación (su propiedad HasDependingSlides es true). |

### Véase también
* clase [`IMasterLayoutSlideCollection`](/slides/python-net/es/aspose.slides/imasterlayoutslidecollection)
* clase [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)