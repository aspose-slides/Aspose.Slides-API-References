---
title: get_visual_bounds method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/graphicalobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Získá vizuální ohraničení tvaru vypočtené z jeho vykresleného obsahu.

### Návratová hodnota

Objekt [`RectangleF`](/slides/python-net/cs/aspose.slides/rectanglef), který představuje vizuální ohraničení tvaru
             v souřadnicích snímku.



```python
def get_visual_bounds(self):
    ...
```


### Poznámky

Vrácený obdélník představuje ohraničení orientované podél os veškerého obsahu
             vytvořeného tvarem během vykreslování v souřadnicovém prostoru snímku.
            
             Tato ohraničení se mohou lišit od modelových ohraničení tvaru
             ([`Shape.x`](/slides/python-net/cs/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/cs/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/cs/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/cs/aspose.slides/shape/height))
             a mohou obsahovat záporné souřadnice, pokud se vykreslený obsah rozprostírá
             za počátek snímku.
            
             Vizuální ohraničení zohledňují aspekty související s vykreslováním, jako jsou
             transformace (například rotace), šířka a spojení tahů,
             rozvržení a přetečení textu, geometrie SmartArt a další efekty rozvržení,
             které ovlivňují finální vzhled tvaru po vykreslení.
            
             Vrácená ohraničení nejsou oříznuta na obdélník snímku.



### Viz také
* class [`GraphicalObject`](/slides/python-net/cs/aspose.slides/graphicalobject)
* class [`RectangleF`](/slides/python-net/cs/aspose.slides/rectanglef)
* module [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)