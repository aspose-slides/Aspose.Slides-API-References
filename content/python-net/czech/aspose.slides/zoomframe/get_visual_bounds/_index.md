---
title: get_visual_bounds method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/zoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Gets the visual bounds of the shape calculated from its rendered content.

### Návratová hodnota

[`RectangleF`](/slides/python-net/cs/aspose.slides/rectanglef) představuje vizuální ohraničení tvaru v souřadnicích snímku.



```python
def get_visual_bounds(self):
    ...
```


### Poznámky

Vrácený obdélník představuje osově zarovnaná ohraničení veškerého obsahu vytvořeného tvarem během vykreslování v souřadnicovém prostoru snímku.

Tato ohraničení se mohou lišit od modelových ohraničení tvaru ([`Shape.x`](/slides/python-net/cs/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/cs/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/cs/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/cs/aspose.slides/shape/height)) a mohou obsahovat záporné souřadnice, pokud se vykreslený obsah rozšiřuje za počátek snímku.

Vizuální ohraničení zohledňují aspekty související s vykreslováním, jako jsou transformace (například otočení), šířka tahu a spoje, rozvržení textu a přetečení, geometrie SmartArt a další efekty rozvržení, které ovlivňují finální vzhled tvaru po vykreslení.

Vrácená ohraničení nejsou ořezána na obdélník snímku.



### Viz také
* třída [`ZoomFrame`](/slides/python-net/cs/aspose.slides/zoomframe)
* třída [`RectangleF`](/slides/python-net/cs/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)