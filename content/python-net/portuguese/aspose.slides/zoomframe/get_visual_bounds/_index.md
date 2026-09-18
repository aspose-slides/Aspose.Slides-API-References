---
title: get_visual_bounds method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/zoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Obtém os limites visuais da forma calculados a partir do seu conteúdo renderizado.

### Retorna

Um **aspose.slides.RectangleF** que representa os limites visuais da forma nas coordenadas do slide.



```python
def get_visual_bounds(self):
    ...
```


### Observações

O retângulo retornado representa os limites alinhados aos eixos de todo o conteúdo produzido pela forma durante a renderização no espaço de coordenadas do slide.

Esses limites podem diferir dos limites do modelo da forma ([`Shape.x`](/slides/python-net/pt/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/pt/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/pt/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/pt/aspose.slides/shape/height)) e podem conter coordenadas negativas se o conteúdo renderizado se estender além da origem do slide.

Os limites visuais levam em conta aspectos relacionados à renderização, como transformações (por exemplo, rotação), largura e junções de traço, layout e transbordamento de texto, geometria do SmartArt e outros efeitos de layout que influenciam a aparência final renderizada da forma.

Os limites retornados não são recortados ao retângulo do slide.



### Veja Também
* classe [`ZoomFrame`](/slides/python-net/pt/aspose.slides/zoomframe)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)