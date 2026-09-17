---
title: remove method
second_title: Referencia de API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides/layoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
Elimina un diseño de la colección.

```python
def remove(self, value):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide) | La diapositiva de diseño que se eliminará de la colección. |

### Observaciones

1) Para evitar lanzar la PptxEditException, compruebe la propiedad HasDependingSlides del diseño antes.  
2) También puede usar el método [`ILayoutSlide.remove`](/slides/python-net/es/aspose.slides/ilayoutslide/remove) para simplificar el código.

### Excepciones

| Excepción | Descripción |
| :- | :- |
| [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception) | Se lanza si el diseño se usa en la presentación (su propiedad HasDependingSlides es true). |

### Ver también
* clase [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide)
* clase [`LayoutSlideCollection`](/slides/python-net/es/aspose.slides/layoutslidecollection)
* clase [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)