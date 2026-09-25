---
title: get_visual_bounds method
second_title: Aspose.Slides dla Pythona poprzez .NET API Reference
description: 
type: docs
url: /pl/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
Pobiera wizualne granice kształtu obliczone z jego renderowanej zawartości.

### Zwraca

A [`RectangleF`](/slides/python-net/pl/aspose.slides/rectanglef) that represents the visual bounds of the shape
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### Uwagi
The returned rectangle represents the axis-aligned bounds of all content
             produced by the shape during rendering in slide coordinate space.
            
             These bounds may differ from the shape's model bounds
             ([`Shape.x`](/slides/python-net/pl/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/pl/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/pl/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/pl/aspose.slides/shape/height))
             and may contain negative coordinates if the rendered content extends
             beyond the slide origin.
            
             The visual bounds take into account rendering-related aspects such as
             transformations (for example, rotation), stroke width and joins,
             text layout and overflow, SmartArt geometry, and other layout effects
             that influence the final rendered appearance of the shape.
            
             The returned bounds are not clipped to the slide rectangle.



### Zobacz także
* klasa [`Chart`](/slides/python-net/pl/aspose.slides.charts/chart)
* klasa [`RectangleF`](/slides/python-net/pl/aspose.slides/rectanglef)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)