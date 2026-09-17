---
title: remove method
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides/masterlayoutslidecollection/remove/
weight: 60
---
## remove(self, value) {#ilayoutslide}
Elimina un layout de la colección.


```python
def remove(self, value):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide) | La diapositiva de layout a eliminar de la colección. |

### Observaciones

1) Para evitar lanzar la PptxEditException, compruebe la propiedad HasDependingSlides del layout antes.
            2) También puede usar el método [`ILayoutSlide.remove`](/slides/python-net/es/aspose.slides/ilayoutslide/remove) para simplificar el código.

### Excepciones

| Excepción | Descripción |
| :- | :- |
| [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception) | Se lanza si el layout se usa en la presentación (su propiedad HasDependingSlides es true). |



### Ver también
* clase [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide)
* clase [`MasterLayoutSlideCollection`](/slides/python-net/es/aspose.slides/masterlayoutslidecollection)
* clase [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)