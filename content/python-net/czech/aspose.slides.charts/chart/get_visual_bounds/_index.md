---
title: get_visual_bounds method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
Získá vizuální ohraničení tvaru vypočtené z jeho vykresleného obsahu.

### Návratová hodnota
A [`RectangleF`](/slides/python-net/cs/aspose.slides/rectanglef) představující vizuální ohraničení tvaru ve souřadnicích snímku.

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
             původ snímku.

Vizuální ohraničení zohledňuje aspekty související s vykreslováním, jako jsou
             transformace (například rotace), šířka tahu a spojení,
             rozvržení textu a přetečení, geometrie SmartArt a další efekty rozvržení,
             které ovlivňují konečný vzhled vykresleného tvaru.

Vrácená ohraničení nejsou oříznuta na obdélník snímku.

### Viz také
* třída [`Chart`](/slides/python-net/cs/aspose.slides.charts/chart)
* třída [`RectangleF`](/slides/python-net/cs/aspose.slides/rectanglef)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)