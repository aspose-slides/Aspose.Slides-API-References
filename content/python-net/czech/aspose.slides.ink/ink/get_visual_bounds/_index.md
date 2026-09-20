---
title: get_visual_bounds method
second_title: Aspose.Slides pro Python prostřednictvím .NET - reference API
description: 
type: docs
url: /cs/aspose.slides.ink/ink/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Získá vizuální ohraničení tvaru vypočítané z jeho vykresleného obsahu.

### Návratová hodnota

Objekt **aspose.slides.RectangleF**, který představuje vizuální ohraničení tvaru v souřadnicích snímku.



```python
def get_visual_bounds(self):
    ...
```


### Poznámky

Vrácený obdélník představuje osově zarovnané ohraničení veškerého obsahu vytvořeného tvarem během vykreslování v souřadnicovém prostoru snímku.

Tato ohraničení se mohou lišit od modelových ohraničení tvaru ([`Shape.x`](/slides/python-net/cs/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/cs/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/cs/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/cs/aspose.slides/shape/height)) a mohou obsahovat záporné souřadnice, pokud vykreslený obsah přesahuje počátek snímku.

Vizuální ohraničení zohledňuje aspekty související s vykreslováním, jako jsou transformace (například otáčení), šířka tahů a spoje, rozvržení a přetečení textu, geometrie SmartArt a další efekty rozvržení, které ovlivňují finální vzhled tvaru po vykreslení.

Vrácená ohraničení nejsou ořezána na obdélník snímku.



### Viz také
* třída [`Ink`](/slides/python-net/cs/aspose.slides.ink/ink)
* modul [`aspose.slides.ink`](/slides/python-net/cs/aspose.slides.ink)
* knihovna [`Aspose.Slides`](/slides/python-net)