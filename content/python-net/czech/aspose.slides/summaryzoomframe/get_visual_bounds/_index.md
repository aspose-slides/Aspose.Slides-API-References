---
title: get_visual_bounds method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/summaryzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Získá vizuální ohraničení tvaru spočtené z jeho vykresleného obsahu.

### Vrací

[`RectangleF`](/slides/python-net/cs/aspose.slides/rectanglef) představuje vizuální ohraničení tvaru
             v souřadnicích snímku.



```python
def get_visual_bounds(self):
    ...
```


### Poznámky

Vrácený obdélník představuje osově zarovnané ohraničení veškerého obsahu
             vytvořeného tvarem během vykreslování v souřadnicovém prostoru snímku.
            
             Tyto ohraničení se mohou lišit od modelových ohraničení tvaru
             ([`Shape.x`](/slides/python-net/cs/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/cs/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/cs/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/cs/aspose.slides/shape/height))
             a mohou obsahovat záporné souřadnice, pokud se vykreslený obsah rozprostírá
             za počáteční bod snímku.
            
             Vizuální ohraničení zohledňují aspekty související s vykreslováním, jako jsou
             transformace (například otáčení), šířka a spojení tahů,
             rozvržení a přetečení textu, geometrie SmartArtu, a další efekty rozvržení,
             které ovlivňují konečný vzhled vykresleného tvaru.
            
             Vrácená ohraničení nejsou oříznuta na obdélník snímku.



### Viz také
* třída [`SummaryZoomFrame`](/slides/python-net/cs/aspose.slides/summaryzoomframe)
* třída [`RectangleF`](/slides/python-net/cs/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)