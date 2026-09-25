---
title: get_visual_bounds method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Gets the visual bounds of the shape calculated from its rendered content.

### Retorno

Um [`RectangleF`](/slides/python-net/pt/aspose.slides/rectanglef) que representa os limites visuais da forma nas coordenadas do slide.



```python
def get_visual_bounds(self):
    ...
```


### Observações
The returned rectangle represents the axis-aligned bounds of all content
             produzidos pela forma durante a renderização no espaço de coordenadas do slide.

             These bounds may differ from the shape's model bounds
             ([`Shape.x`](/slides/python-net/pt/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/pt/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/pt/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/pt/aspose.slides/shape/height))
             e podem conter coordenadas negativas se o conteúdo renderizado se estender
             além da origem do slide.

             The visual bounds take into account rendering-related aspects such as
             transformações (por exemplo, rotação), largura e junções de traçado,
             layout de texto e transbordamento, geometria do SmartArt e outros efeitos de layout
             que influenciam a aparência final renderizada da forma.

             The returned bounds are not clipped to the slide rectangle.



### Veja Também
* classe [`SmartArt`](/slides/python-net/pt/aspose.slides.smartart/smartart)
* classe [`RectangleF`](/slides/python-net/pt/aspose.slides/rectanglef)
* módulo [`aspose.slides.smartart`](/slides/python-net/pt/aspose.slides.smartart)
* biblioteca [`Aspose.Slides`](/slides/python-net)