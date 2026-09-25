---
title: get_visual_bounds method
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Vrací vizuální ohraničení tvaru vypočítané z jeho vykresleného obsahu.

### Návratová hodnota

Objekt [`RectangleF`](/slides/python-net/cs/aspose.slides/rectanglef) představující vizuální ohraničení tvaru
             v souřadnicích snímku.

```python
def get_visual_bounds(self):
    ...
```

### Poznámky

Vrácený obdélník představuje osově zarovnané ohraničení veškerého obsahu
             vytvořeného tvarem během vykreslování v souřadnicovém prostoru snímku.

             Tato ohraničení se mohou lišit od modelových ohraničení tvaru
             ([`Shape.x`](/slides/python-net/cs/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/cs/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/cs/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/cs/aspose.slides/shape/height))
             a mohou obsahovat záporné souřadnice, pokud vykreslený obsah přesahuje
             počátek snímku.

             Vizuální ohraničení zohledňuje aspekty související s vykreslováním, jako jsou transformace (například rotace), šířka tahu a spáry, rozvržení a přetečení textu, geometrie SmartArtu a další efekty rozvržení, které ovlivňují konečný vykreslený vzhled tvaru.

             Vrácená ohraničení nejsou oříznuta na obdélník snímku.

### Viz také
* třída [`SmartArt`](/slides/python-net/cs/aspose.slides.smartart/smartart)
* třída [`RectangleF`](/slides/python-net/cs/aspose.slides/rectanglef)
* modul [`aspose.slides.smartart`](/slides/python-net/cs/aspose.slides.smartart)
* knihovna [`Aspose.Slides`](/slides/python-net)