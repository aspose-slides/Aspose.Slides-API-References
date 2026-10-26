---
title: add_clone method
second_title: Referencia de la API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/masterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Añade una copia de una diapositiva de diseño especificada al final de la colección.

### Devuelve

Diapositiva agregada.



```python
def add_clone(self, source_layout):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide) | Diapositiva a clonar. |

### Observaciones

1) El nuevo diseño se vinculará con la diapositiva maestra principal de esta colección de diapositivas de diseño.  
   Por lo tanto, esto es análogo a copiar/pegar con la opción "Usar tema de destino" en PowerPoint.  
2) El análogo de este método es el método **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** accedido con la propiedad [`IPresentation.layout_slides`](/slides/python-net/es/aspose.slides/ipresentation/layout_slides).



### Véase también
* clase [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide)
* clase [`MasterLayoutSlideCollection`](/slides/python-net/es/aspose.slides/masterlayoutslidecollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)