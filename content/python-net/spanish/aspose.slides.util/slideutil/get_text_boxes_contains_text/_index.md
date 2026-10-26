---
title: get_text_boxes_contains_text method
second_title: Referencia de API de Aspose.Slides para Python via .NET
description: 
type: docs
url: /es/aspose.slides.util/slideutil/get_text_boxes_contains_text/
weight: 70
---
## get_text_boxes_contains_text(slide, text, check_placeholder_text) {#ibaseslide-str-bool}
Devuelve todos los marcos de texto en la diapositiva especificada que contienen el texto dado.

### Devuelve

Una matriz de objetos [`ITextFrame`](/slides/python-net/es/aspose.slides/itextframe) que contienen el texto especificado.



```python
@staticmethod
def get_text_boxes_contains_text(slide, text, check_placeholder_text):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/es/aspose.slides/ibaseslide) | La diapositiva donde buscar. |
| text | **str** | El texto a buscar dentro de los marcos de texto. |
| check_placeholder_text | **bool** | Indica si se deben incluir los marcos de texto que están vacíos, pero cuyo texto de marcador de posición contiene el texto de búsqueda. |



### Ver también
* clase [`IBaseSlide`](/slides/python-net/es/aspose.slides/ibaseslide)
* clase [`ITextFrame`](/slides/python-net/es/aspose.slides/itextframe)
* clase [`SlideUtil`](/slides/python-net/es/aspose.slides.util/slideutil)
* módulo [`aspose.slides.util`](/slides/python-net/es/aspose.slides.util)
* biblioteca [`Aspose.Slides`](/slides/python-net)