---
title: get_visual_bounds method
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides/zoomobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Obtiene los límites visuales de la forma calculados a partir de su contenido renderizado.

### Devuelve

Un [`RectangleF`](/slides/python-net/es/aspose.slides/rectanglef) que representa los límites visuales de la forma
             en coordenadas de diapositiva.



```python
def get_visual_bounds(self):
    ...
```


### Observaciones
The returned rectangle represents the axis-aligned bounds of all content
             produced by the shape during rendering in slide coordinate space.
            
             These bounds may differ from the shape's model bounds
             ([`Shape.x`](/slides/python-net/es/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/es/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/es/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/es/aspose.slides/shape/height))
             and may contain negative coordinates if the rendered content extends
             beyond the slide origin.
            
             The visual bounds take into account rendering-related aspects such as
             transformations (for example, rotation), stroke width and joins,
             text layout and overflow, SmartArt geometry, and other layout effects
             that influence the final rendered appearance of the shape.
            
             The returned bounds are not clipped to the slide rectangle.



### Ver también
* clase [`ZoomObject`](/slides/python-net/es/aspose.slides/zoomobject)
* clase [`RectangleF`](/slides/python-net/es/aspose.slides/rectanglef)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)