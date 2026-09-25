---
title: get_visual_bounds method
second_title: Aspose.Slides برای پایتون از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides/oleobjectframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Gets the visual bounds of the shape calculated from its rendered content.

### بازگشت

A [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef) that represents the visual bounds of the shape
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### نکات

The returned rectangle represents the axis-aligned bounds of all content
               produced by the shape during rendering in slide coordinate space.

               These bounds may differ from the shape's model bounds
               ([`Shape.x`](/slides/python-net/fa/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/fa/aspose.slides/shape/y),
               [`Shape.width`](/slides/python-net/fa/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/fa/aspose.slides/shape/height))
               and may contain negative coordinates if the rendered content extends
               beyond the slide origin.

               The visual bounds take into account rendering-related aspects such as
               transformations (for example, rotation), stroke width and joins,
               text layout and overflow, SmartArt geometry, and other layout effects
               that influence the final rendered appearance of the shape.

               The returned bounds are not clipped to the slide rectangle.



### موارد مرتبط
* کلاس [`OleObjectFrame`](/slides/python-net/fa/aspose.slides/oleobjectframe)
* کلاس [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)