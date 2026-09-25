---
title: get_visual_bounds method
second_title: Aspose.Slides pro Python přes .NET API referenci
description: 
type: docs
url: /cs/aspose.slides/groupshape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Získá vizuální ohraničení tvaru vypočítané z jeho vykresleného obsahu.

### Návrat
[`RectangleF`](/slides/python-net/cs/aspose.slides/rectanglef) představuje vizuální ohraničení tvaru ve souřadnicích snímku.

```python
def get_visual_bounds(self):
    ...
```

### Poznámky
Vrácený obdélník představuje osově zarovnané ohraničení veškerého obsahu vytvořeného tvarem během vykreslování v souřadnicovém prostoru snímku.

Tato ohraničení se mohou lišit od modelových ohraničení tvaru ([`Shape.x`](/slides/python-net/cs/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/cs/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/cs/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/cs/aspose.slides/shape/height)) a mohou obsahovat záporné souřadnice, pokud vykreslený obsah přesahuje počátek snímku.

Vizuální ohraničení zohledňují aspekty související s vykreslováním, jako jsou transformace (například rotace), šířka obrysu a napojení, rozvržení textu a přetečení, geometrie SmartArt a další efekty rozvržení, které ovlivňují konečný vzhled tvaru po vykreslení.

Vrácená ohraničení nejsou oříznuta na obdélník snímku.

### Viz také
* třída [`GroupShape`](/slides/python-net/cs/aspose.slides/groupshape)
* třída [`RectangleF`](/slides/python-net/cs/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)