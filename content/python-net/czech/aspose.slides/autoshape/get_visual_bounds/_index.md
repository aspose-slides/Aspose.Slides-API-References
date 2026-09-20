---
title: get_visual_bounds method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
Získá vizuální ohraničení objektu vypočtené z jeho vykresleného obsahu.

### Vrací

Objekt **aspose.slides.RectangleF**, který představuje vizuální ohraničení objektu ve souřadnicích snímku.



```python
def get_visual_bounds(self):
    ...
```


### Poznámky

Vrácený obdélník představuje osově zarovnané ohraničení veškerého obsahu vytvořeného objektem během vykreslování v souřadnicovém prostoru snímku.

Tato ohraničení se mohou lišit od modelových ohraničení objektu ([`Shape.x`](/slides/python-net/cs/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/cs/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/cs/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/cs/aspose.slides/shape/height)) a mohou obsahovat záporné souřadnice, pokud vykreslený obsah přesahuje počátek snímku.

Vizuální ohraničení zohledňuje aspekty související s vykreslováním, jako jsou transformace (například otáčení), šířka tahu a spojení, rozvržení textu a překročení, geometrie SmartArt a další efekty rozvržení, které ovlivňují konečný vykreslený vzhled objektu.

Vrácená ohraničení nejsou oříznuta na obdélník snímku.



### Viz také
* třída [`AutoShape`](/slides/python-net/cs/aspose.slides/autoshape)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)