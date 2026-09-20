---
title: get_visual_bounds method
second_title: Aspose.Slides pro Python přes .NET – referenční příručka API
description: 
type: docs
url: /cs/aspose.slides/legacydiagram/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Získá vizuální hranice tvaru vypočtené z jeho vykresleného obsahu.

### Vrací

Objekt **aspose.slides.RectangleF**, který představuje vizuální hranice tvaru
             ve souřadnicích snímku.



```python
def get_visual_bounds(self):
    ...
```


### Poznámky

Vrácený obdélník představuje osově zarovnané hranice veškerého obsahu vytvořeného tvarem během vykreslování v souřadnicovém prostoru snímku.
            
Tyto hranice se mohou lišit od modelových hranic tvaru ([`Shape.x`](/slides/python-net/cs/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/cs/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/cs/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/cs/aspose.slides/shape/height))
a mohou obsahovat záporné souřadnice, pokud vykreslený obsah přesahuje původ snímku.
            
Vizuální hranice zohledňují aspekty související s vykreslováním, jako jsou transformace (například rotace), šířka a spojení tahů, rozvržení a přetečení textu, geometrie SmartArt a další efekty rozvržení, které ovlivňují konečný vzhled vykresleného tvaru.
            
Vrácené hranice nejsou oříznuty na obdélník snímku.



### Viz také
* třída [`LegacyDiagram`](/slides/python-net/cs/aspose.slides/legacydiagram)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)