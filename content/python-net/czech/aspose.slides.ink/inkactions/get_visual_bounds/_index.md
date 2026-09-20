---
title: get_visual_bounds method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.ink/inkactions/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Získá vizuální ohraničení objektu vypočtené z jeho vykresleného obsahu.

### Návratová hodnota

Objekt **aspose.slides.RectangleF**, který představuje vizuální ohraničení objektu
             v souřadnicích snímku.



```python
def get_visual_bounds(self):
    ...
```


### Poznámky

Vrácený obdélník představuje osově zarovnané ohraničení veškerého obsahu vytvořeného objektem během vykreslování v souřadnicovém prostoru snímku.
             
             Tato ohraničení se mohou lišit od modelových ohraničení objektu ([`Shape.x`](/slides/python-net/cs/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/cs/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/cs/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/cs/aspose.slides/shape/height)) a mohou obsahovat záporné souřadnice, pokud vykreslený obsah přesahuje počátek snímku.
             
             Vizuální ohraničení zohledňuje aspekty související s vykreslováním, jako jsou transformace (například otáčení), šířka tahy a spoje,
             rozvržení a přetečení textu, geometrie SmartArt a další efekty rozvržení, které ovlivňují finální vzhled objektu při vykreslování.
             
             Vrácená ohraničení nejsou oříznuta na obdélník snímku.



### Viz také
* třída [`InkActions`](/slides/python-net/cs/aspose.slides.ink/inkactions)
* modul [`aspose.slides.ink`](/slides/python-net/cs/aspose.slides.ink)
* knihovna [`Aspose.Slides`](/slides/python-net)