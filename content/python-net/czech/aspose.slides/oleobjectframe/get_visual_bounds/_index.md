---
title: get_visual_bounds method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/oleobjectframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Získá vizuální ohraničení tvaru vypočítané z jeho vykresleného obsahu.

### Návratová hodnota

[`RectangleF`](/slides/python-net/cs/aspose.slides/rectanglef) představuje vizuální ohraničení tvaru v souřadnicích snímku.



```python
def get_visual_bounds(self):
    ...
```


### Poznámky

Vrácený obdélník představuje osově zarovnané ohraničení veškerého obsahu vytvořeného tvarem během vykreslování v souřadnicovém prostoru snímku.

Tato ohraničení se mohou lišit od modelových ohraničení tvaru ([`Shape.x`](/slides/python-net/cs/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/cs/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/cs/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/cs/aspose.slides/shape/height)) a mohou obsahovat záporné souřadnice, pokud vykreslený obsah přesahuje počátek snímku.

Vizuální ohraničení zohledňuje aspekty související s vykreslováním, jako jsou transformace (například otáčení), šířka tahu a spoje, rozvržení a přetečení textu, geometrie SmartArt a další efekty rozvržení, které ovlivňují konečný vzhled tvaru po vykreslení.

Vrácená ohraničení nejsou oříznuta na obdélník snímku.



### Viz také
* třída [`OleObjectFrame`](/slides/python-net/cs/aspose.slides/oleobjectframe)
* třída [`RectangleF`](/slides/python-net/cs/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)