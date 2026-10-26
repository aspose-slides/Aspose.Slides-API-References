---
title: remove method
second_title: Referencia de la API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides/ilayoutslide/remove/
weight: 60
---
## remove(self) {#}
Elimina el diseño de la presentación.

```python
def remove(self):
    ...
```

### Observaciones

Para evitar lanzar la PptxEditException, comprueba la propiedad HasDependingSlides del diseño antes.

### Excepciones

| Excepción | Descripción |
| :- | :- |
| [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception) | Lanzada si el diseño ya está eliminado de la presentación o si el diseño se usa en la presentación (su <br/>            HasDependingSlides propiedad es verdadera). |

### Ver también
* clase [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide)
* clase [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)