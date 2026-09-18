---
title: get_visual_bounds method
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
Obtém os limites visuais da forma calculados a partir de seu conteúdo renderizado.

### Retorna

Um **aspose.slides.RectangleF** que representa os limites visuais da forma nas coordenadas do slide.



```python
def get_visual_bounds(self):
    ...
```


### Observações

O retângulo retornado representa os limites alinhados aos eixos de todo o conteúdo gerado pela forma durante a renderização no espaço de coordenadas do slide.

Esses limites podem diferir dos limites de modelo da forma ([`Shape.x`](/slides/python-net/pt/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/pt/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/pt/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/pt/aspose.slides/shape/height)) e podem conter coordenadas negativas se o conteúdo renderizado se estender além da origem do slide.

Os limites visuais levam em conta aspectos relacionados à renderização, como transformações (por exemplo, rotação), largura e junções de traço, layout e estouro de texto, geometria do SmartArt e outros efeitos de layout que influenciam a aparência renderizada final da forma.

Os limites retornados não são recortados ao retângulo do slide.



### Veja também
* classe [`Chart`](/slides/python-net/pt/aspose.slides.charts/chart)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)