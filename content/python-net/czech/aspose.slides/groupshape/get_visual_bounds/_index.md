---
title: get_visual_bounds method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/groupshape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Získá vizuální ohraničení tvaru vypočítané z jeho vykresleného obsahu.

### Návratová hodnota

A **aspose.slides.RectangleF** that represents the visual bounds of the shape
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### Poznámky

The returned rectangle represents the axis-aligned bounds of all content
             produced by the shape during rendering in slide coordinate space.
            
Tyto ohraničení se mohou lišit od modelových ohraničení tvaru
             ([`Shape.x`](/slides/python-net/cs/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/cs/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/cs/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/cs/aspose.slides/shape/height))
             a mohou obsahovat záporné souřadnice, pokud vykreslený obsah přesahuje
             počátek snímku.
            
Vizuální ohraničení zohledňují aspekty související s vykreslováním, jako jsou
 transformations (for example, rotation), stroke width and joins,
 text layout and overflow, SmartArt geometry, and other layout effects
 that influence the final rendered appearance of the shape.
            
Vrácená ohraničení nejsou oříznuta na obdélník snímku.



### Viz také
* třída [`GroupShape`](/slides/python-net/cs/aspose.slides/groupshape)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)