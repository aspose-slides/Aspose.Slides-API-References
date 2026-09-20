---
title: get_visual_bounds method
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Získá vizuální ohraničení tvaru vypočtené z jeho vykresleného obsahu.

### Návratová hodnota

**aspose.slides.RectangleF** představuje vizuální ohraničení tvaru
             v souřadnicích snímku.



```python
def get_visual_bounds(self):
    ...
```


### Poznámky

Obdržený obdélník představuje osově zarovnané ohraničení veškerého obsahu
             vytvořeného tvarem během vykreslování v souřadnicovém prostoru snímku.
            
             Tato ohraničení se mohou lišit od modelových ohraničení tvaru
             ([`Shape.x`](/slides/python-net/cs/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/cs/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/cs/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/cs/aspose.slides/shape/height))
             a mohou obsahovat záporné souřadnice, pokud vykreslený obsah přesahuje
             počátek snímku.
            
             Vizuální ohraničení bere v úvahu aspekty související s vykreslováním,
             jako jsou transformace (například rotace), šířka tahu a spoje,
             rozvržení textu a přetečení, geometrie SmartArt a další efekty rozvržení,
             které ovlivňují finální vzhled tvaru po vykreslení.
            
             Obdržená ohraničení nejsou oříznuta na obdélník snímku.



### Viz také
* třída [`SmartArtShape`](/slides/python-net/cs/aspose.slides.smartart/smartartshape)
* modul [`aspose.slides.smartart`](/slides/python-net/cs/aspose.slides.smartart)
* knihovna [`Aspose.Slides`](/slides/python-net)