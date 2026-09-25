---
title: get_visual_bounds method
second_title: Aspose.Slides Python számára .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides/connector/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Lekéri a forma vizuális határait, amelyeket a megjelenített tartalom alapján számítanak ki.

### Visszatér

A [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef) amely a forma vizuális határait jeleníti meg diavetítés koordinátákban.



```python
def get_visual_bounds(self):
    ...
```


### Megjegyzések
The returned rectangle represents the axis-aligned bounds of all content
             produced by the shape during rendering in slide coordinate space.
            
             These bounds may differ from the shape's model bounds
             ([`Shape.x`](/slides/python-net/hu/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/hu/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/hu/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/hu/aspose.slides/shape/height))
             and may contain negative coordinates if the rendered content extends
             beyond the slide origin.
            
             The visual bounds take into account rendering-related aspects such as
             transformations (for example, rotation), stroke width and joins,
             text layout and overflow, SmartArt geometry, and other layout effects
             that influence the final rendered appearance of the shape.
            
             The returned bounds are not clipped to the slide rectangle.



### Lásd még
* osztály [`Connector`](/slides/python-net/hu/aspose.slides/connector)
* osztály [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)