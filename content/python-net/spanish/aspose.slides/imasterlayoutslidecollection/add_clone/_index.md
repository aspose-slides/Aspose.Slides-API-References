---
title: add_clone method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/imasterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Añade una copia de una diapositiva de diseño especificada al final de la colección.

### Devuelve

Diapositiva añadida.



```python
def add_clone(self, source_layout):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide) | Diapositiva a clonar. |

### Observaciones

1) El nuevo diseño se vinculará con la diapositiva maestra principal de esta colección de diapositivas de diseño. Por lo tanto, esto es análogo a copiar/pegar con la opción "Use Destination Theme" en PowerPoint.  
2) Análogo a este método es el método **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** accedido mediante la propiedad [`IPresentation.layout_slides`](/slides/python-net/es/aspose.slides/ipresentation/layout_slides).



### Ver también
* clase [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide)
* clase [`IMasterLayoutSlideCollection`](/slides/python-net/es/aspose.slides/imasterlayoutslidecollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)