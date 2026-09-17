---
title: remove method
second_title: Referencia de la API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/layoutslide/remove/
weight: 60
---
## remove(self) {#}
Elimina el diseño de la presentación.

```python
def remove(self):
    ...
```

### Observaciones

Para evitar lanzar la PptxEditException, compruebe antes la propiedad HasDependingSlides del diseño.

### Excepciones

| Excepción | Descripción |
| :- | :- |
| [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception) | Se lanza si el diseño ya está eliminado de la presentación o si el diseño se usa en la presentación (su <br/>            propiedad HasDependingSlides es verdadera). |

### Véase también
* clase [`LayoutSlide`](/slides/python-net/es/aspose.slides/layoutslide)
* clase [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)