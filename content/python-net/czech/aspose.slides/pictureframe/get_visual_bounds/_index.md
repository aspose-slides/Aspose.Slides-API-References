---
title: get_visual_bounds method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/pictureframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Získá vizuální ohraničení tvaru vypočítané z jeho vykresleného obsahu.

### Vrací

Objekt **aspose.slides.RectangleF**, který představuje vizuální ohraničení tvaru
             v souřadnicích snímku.



```python
def get_visual_bounds(self):
    ...
```


### Poznámky
Vrácený obdélník představuje osově zarovnaná ohraničení veškerého obsahu
             vytvořeného tvarem během vykreslování v souřadnicovém prostoru snímku.
            
             Tato ohraničení se mohou lišit od modelových ohraničení tvaru
             ([`Shape.x`](/slides/python-net/cs/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/cs/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/cs/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/cs/aspose.slides/shape/height))
             a mohou obsahovat záporné souřadnice, pokud se vykreslený obsah rozšiřuje
             za počátek snímku.
            
             Vizuální ohraničení zohledňuje aspekty související s vykreslováním, jako jsou
             transformace (například rotace), šířka tahů a spojení,
             rozvržení a přetečení textu, geometrie SmartArt a další efekty rozvržení,
             které ovlivňují finální vzhled tvaru po vykreslení.
            
             Vrácená ohraničení nejsou oříznuta na obdélník snímku.



### Viz také
* třída [`PictureFrame`](/slides/python-net/cs/aspose.slides/pictureframe)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)