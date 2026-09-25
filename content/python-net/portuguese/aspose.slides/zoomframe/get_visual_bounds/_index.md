---
title: get_visual_bounds method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/zoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Obtém os limites visuais da forma calculados a partir de seu conteúdo renderizado.

### Retorna

Um [`RectangleF`](/slides/python-net/pt/aspose.slides/rectanglef) que representa os limites visuais da forma nas coordenadas do slide.



```python
def get_visual_bounds(self):
    ...
```


### Observações
The returned rectangle represents the axis-aligned bounds of all content
             produced by the shape during rendering in slide coordinate space.
            
             These bounds may differ from the shape's model bounds
             ([`Shape.x`](/slides/python-net/pt/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/pt/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/pt/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/pt/aspose.slides/shape/height))
             and may contain negative coordinates if the rendered content extends
             beyond the slide origin.
            
             The visual bounds take into account rendering-related aspects such as
             transformations (for example, rotation), stroke width and joins,
             text layout and overflow, SmartArt geometry, and other layout effects
             that influence the final rendered appearance of the shape.
            
             The returned bounds are not clipped to the slide rectangle.



### Ver Também
* classe [`ZoomFrame`](/slides/python-net/pt/aspose.slides/zoomframe)
* classe [`RectangleF`](/slides/python-net/pt/aspose.slides/rectanglef)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)