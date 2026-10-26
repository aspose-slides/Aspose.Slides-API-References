---
title: get_visual_bounds method
second_title: Aspose.Slides pro Python přes .NET referenční příručku API
description: 
type: docs
url: /cs/aspose.slides/connector/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Získá vizuální ohraničení tvaru vypočtené z jeho vykresleného obsahu.

### Návratová hodnota

[`RectangleF`](/slides/python-net/cs/aspose.slides/rectanglef) představuje vizuální ohraničení tvaru v souřadnicích snímku.



```python
def get_visual_bounds(self):
    ...
```


### Poznámky
Vrácený obdélník představuje osově zarovnané ohraničení veškerého obsahu vytvořeného tvarem během renderování v souřadnicovém prostoru snímku.
            
            Tyto ohraničení se mohou lišit od modelových ohraničení tvaru ([`Shape.x`](/slides/python-net/cs/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/cs/aspose.slides/shape/y),
            [`Shape.width`](/slides/python-net/cs/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/cs/aspose.slides/shape/height)) a mohou obsahovat záporné souřadnice, pokud vykreslený obsah přesahuje počátek snímku.
            
            Vizuální ohraničení zohledňuje aspekty související s renderováním, jako jsou transformace (například rotace), šířka tahů a spojení, rozvržení textu a přetečení, geometrie SmartArt a další efekty rozvržení, které ovlivňují konečný vzhled tvaru při vykreslení.
            
            Vrácená ohraničení nejsou ořezána na obdélník snímku.



### Viz také
* třída [`Connector`](/slides/python-net/cs/aspose.slides/connector)
* třída [`RectangleF`](/slides/python-net/cs/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)