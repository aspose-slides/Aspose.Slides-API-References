---
title: get_visual_bounds method
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
Obtiene los límites visuales de la forma calculados a partir de su contenido renderizado.

### Devuelve

Un **aspose.slides.RectangleF** que representa los límites visuales de la forma en coordenadas de la diapositiva.



```python
def get_visual_bounds(self):
    ...
```


### Comentarios

El rectángulo devuelto representa los límites alineados al eje de todo el contenido producido por la forma durante el renderizado en el espacio de coordenadas de la diapositiva.
            
            Estos límites pueden diferir de los límites del modelo de la forma
            ([`Shape.x`](/slides/python-net/es/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/es/aspose.slides/shape/y),
            [`Shape.width`](/slides/python-net/es/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/es/aspose.slides/shape/height))
            y pueden contener coordenadas negativas si el contenido renderizado se extiende más allá del origen de la diapositiva.
            
            Los límites visuales tienen en cuenta aspectos relacionados con el renderizado, como transformaciones (por ejemplo, rotación), ancho y uniones de trazo, disposición y desbordamiento del texto, geometría de SmartArt y otros efectos de diseño que influyen en la apariencia final renderizada de la forma.
            
            Los límites devueltos no se recortan al rectángulo de la diapositiva.



### Ver también
* clase [`AutoShape`](/slides/python-net/es/aspose.slides/autoshape)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)