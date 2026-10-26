---
title: get_visual_bounds method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.ink/inkactions/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Získá vizuální ohraničení objektu vypočítané z jeho vykresleného obsahu.

### Návratová hodnota

[`RectangleF`](/slides/python-net/cs/aspose.slides/rectanglef) představuje vizuální ohraničení objektu v souřadnicích snímku.



```python
def get_visual_bounds(self):
    ...
```


### Poznámky

Vrácený obdélník představuje osově zarovnaná ohraničení veškerého obsahu vygenerovaného objektem během vykreslování v souřadnicovém prostoru snímku.

Tyto ohraničení se mohou lišit od modelových ohraničení objektu ([`Shape.x`](/slides/python-net/cs/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/cs/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/cs/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/cs/aspose.slides/shape/height)) a mohou obsahovat záporné souřadnice, pokud vykreslený obsah přesahuje počátek snímku.

Vizuální ohraničení zohledňují aspekty související s vykreslováním, jako jsou transformace (například otočení), šířka a spojení tahů, rozvržení a přetečení textu, geometrie SmartArt a další efekty rozvržení, které ovlivňují finální vzhled objektu.

Vrácená ohraničení nejsou oříznuta na obdélník snímku.



### Viz také
* třída [`InkActions`](/slides/python-net/cs/aspose.slides.ink/inkactions)
* třída [`RectangleF`](/slides/python-net/cs/aspose.slides/rectanglef)
* modul [`aspose.slides.ink`](/slides/python-net/cs/aspose.slides.ink)
* library [`Aspose.Slides`](/slides/python-net)