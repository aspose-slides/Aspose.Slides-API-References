---
title: get_visual_bounds method
second_title: Tham khảo API .NET của Aspose.Slides cho Python
description: 
type: docs
url: /vi/aspose.slides/graphicalobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Lấy giới hạn trực quan của đối tượng hình được tính từ nội dung đã được vẽ.

### Trả về

A **aspose.slides.RectangleF** that represents the visual bounds of the shape
             in slide coordinates.

```python
def get_visual_bounds(self):
    ...
```

### Ghi chú

The returned rectangle represents the axis-aligned bounds of all content
             produced by the shape during rendering in slide coordinate space.
            
             These bounds may differ from the shape's model bounds
             ([`Shape.x`](/slides/python-net/vi/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/vi/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/vi/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/vi/aspose.slides/shape/height))
             and may contain negative coordinates if the rendered content extends
             beyond the slide origin.
            
             The visual bounds take into account rendering-related aspects such as
             transformations (for example, rotation), stroke width and joins,
             text layout and overflow, SmartArt geometry, and other layout effects
             that influence the final rendered appearance of the shape.
            
             The returned bounds are not clipped to the slide rectangle.

### Xem thêm
* lớp [`GraphicalObject`](/slides/python-net/vi/aspose.slides/graphicalobject)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)