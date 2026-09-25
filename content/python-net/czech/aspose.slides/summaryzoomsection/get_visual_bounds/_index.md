---
title: get_visual_bounds method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/summaryzoomsection/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Získá vizuální ohraničení shape vypočtené z jeho renderovaného obsahu.

### Návratová hodnota

Objekt [`RectangleF`](/slides/python-net/cs/aspose.slides/rectanglef), který představuje vizuální ohraničení shape
             ve slide souřadnicích.

```python
def get_visual_bounds(self):
    ...
```

### Poznámky

Vrácený rectangle představuje osově zarovnané ohraničení veškerého obsahu vytvořeného shape během renderování ve slide souřadnicovém prostoru.

Tyto ohraničení se mohou lišit od modelových ohraničení shape ([`Shape.x`](/slides/python-net/cs/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/cs/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/cs/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/cs/aspose.slides/shape/height)) a mohou obsahovat záporné souřadnice, pokud vykreslený obsah přesahuje původ slide.

Vizuální ohraničení zohledňuje aspekty související s renderováním, jako jsou transformace (například rotace), šířka tahu a spoje, rozvržení textu a přetečení, geometrie SmartArt a další efekty rozvržení, které ovlivňují konečný vzhled renderovaného shape.

Vrácená ohraničení nejsou oříznuta na rectangle slide.

### Viz také
* třída [`SummaryZoomSection`](/slides/python-net/cs/aspose.slides/summaryzoomsection)
* třída [`RectangleF`](/slides/python-net/cs/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)