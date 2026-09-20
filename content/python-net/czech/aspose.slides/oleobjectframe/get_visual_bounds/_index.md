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

Objekt **aspose.slides.RectangleF**, který představuje vizuální ohraničení tvaru v souřadnicích snímku.



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
             a mohou obsahovat záporné souřadnice, pokud vykreslený obsah přesahuje
             původ snímku.

             Vizuální ohraničení zohledňuje aspekty související s vykreslováním, jako jsou
             transformace (například rotace), šířka tahu a spoje,
             rozložení textu a přetečení, geometrie SmartArt a další efekty rozložení,
             které ovlivňují finální vykreslený vzhled tvaru.

             Vrácená ohraničení nejsou oříznuta na obdélník snímku.



### Viz také
* třída [`OleObjectFrame`](/slides/python-net/cs/aspose.slides/oleobjectframe)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)