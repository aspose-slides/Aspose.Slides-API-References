---
title: remove method
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides/globallayoutslidecollection/remove/
weight: 40
---
## remove(self, value) {#ilayoutslide}
Elimina un diseño de la colección.

```python
def remove(self, value):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide) | El diseño de diapositiva que se eliminará de la colección. |

### Observaciones

1) Para evitar que se lance la PptxEditException, compruebe antes la propiedad HasDependingSlides del diseño.  
2) También puede usar el método [`ILayoutSlide.remove`](/slides/python-net/es/aspose.slides/ilayoutslide/remove) para simplificar el código.

### Excepciones

| Excepción | Descripción |
| :- | :- |
| [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception) | Lanzada si el diseño se utiliza en la presentación (su propiedad HasDependingSlides es verdadera). |

### Ver también
* clase [`GlobalLayoutSlideCollection`](/slides/python-net/es/aspose.slides/globallayoutslidecollection)
* clase [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide)
* clase [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)