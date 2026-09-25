---
title: get_visual_bounds method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/table/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Získá vizuální ohraničení tvaru vypočtené z jeho vykresleného obsahu.

### Returns

Objekt [`RectangleF`](/slides/python-net/cs/aspose.slides/rectanglef), který představuje vizuální ohraničení tvaru
             v souřadnicích snímku.



```python
def get_visual_bounds(self):
    ...
```


### Remarks

Vrácený obdélník představuje osově zarovnaná ohraničení veškerého obsahu
             vytvořeného tvarem během vykreslování v souřadnicovém prostoru snímku.
            
Tato ohraničení se mohou lišit od modelových ohraničení tvaru
             ([`Shape.x`](/slides/python-net/cs/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/cs/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/cs/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/cs/aspose.slides/shape/height))
 a mohou obsahovat záporné souřadnice, pokud vykreslený obsah přesahuje
             původ snímku.
            
Vizuální ohraničení zohledňuje aspekty související s vykreslováním, jako jsou
             transformace (například otočení), šířka tahu a spojení,
             rozvržení a přetečení textu, geometrie SmartArt a další efekty rozvržení
             které ovlivňují konečný vykreslený vzhled tvaru.
            
Vrácená ohraničení nejsou oříznuta na obdélník snímku.



### See Also
* třída [`Table`](/slides/python-net/cs/aspose.slides/table)
* třída [`RectangleF`](/slides/python-net/cs/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)