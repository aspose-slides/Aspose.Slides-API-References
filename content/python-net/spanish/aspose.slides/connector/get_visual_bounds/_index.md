---
title: get_visual_bounds method
second_title: Aspose.Slides para Python a través de la API .NET
description: 
type: docs
url: /es/aspose.slides/connector/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Obtiene los límites visuales de la forma calculados a partir de su contenido renderizado.

### Returns

Un **aspose.slides.RectangleF** que representa los límites visuales de la forma
             en coordenadas de la diapositiva.



```python
def get_visual_bounds(self):
    ...
```


### Remarks

El rectángulo devuelto representa los límites alineados con los ejes de todo el contenido producido por la forma durante el renderizado en el espacio de coordenadas de la diapositiva.
            
            Estos límites pueden diferir de los límites del modelo de la forma
            ([`Shape.x`](/slides/python-net/es/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/es/aspose.slides/shape/y),
            [`Shape.width`](/slides/python-net/es/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/es/aspose.slides/shape/height))
            y pueden contener coordenadas negativas si el contenido renderizado se extiende más allá del origen de la diapositiva.
            
            Los límites visuales tienen en cuenta aspectos relacionados con el renderizado, como transformaciones (por ejemplo, rotación), ancho y uniones de trazo, diseño y desbordamiento de texto, geometría de SmartArt, y otros efectos de diseño que influyen en la apariencia final renderizada de la forma.
            
            Los límites devueltos no están recortados al rectángulo de la diapositiva.



### See Also
* clase [`Connector`](/slides/python-net/es/aspose.slides/connector)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)