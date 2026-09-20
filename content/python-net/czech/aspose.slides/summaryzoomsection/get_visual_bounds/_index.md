---
title: get_visual_bounds method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/summaryzoomsection/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Získá vizuální meze tvaru vypočítané z jeho vykresleného obsahu.

### Návratová hodnota

**aspose.slides.RectangleF**, který představuje vizuální meze tvaru
             v souřadnicích snímku.



```python
def get_visual_bounds(self):
    ...
```


### Poznámky

Vrácený obdélník představuje osově zarovnané meze veškerého obsahu
             vytvořeného tvarem během vykreslování v prostoru souřadnic snímku.
            
             Tyto meze se mohou lišit od modelových mezí tvaru
             ([`Shape.x`](/slides/python-net/cs/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/cs/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/cs/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/cs/aspose.slides/shape/height))
             a mohou obsahovat záporné souřadnice, pokud vykreslený obsah přesahuje
             počátek snímku.
            
             Vizuální meze zohledňují aspekty související s vykreslováním, jako jsou
             transformace (například otáčení), šířka okraje a spojení,
             rozvržení textu a přetečení, geometrie SmartArt a další efekty rozložení,
             které ovlivňují konečný vzhled tvaru po vykreslení.
            
             Vrácené meze nejsou oříznuty na obdélník snímku.



### Viz také
* třída [`SummaryZoomSection`](/slides/python-net/cs/aspose.slides/summaryzoomsection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)