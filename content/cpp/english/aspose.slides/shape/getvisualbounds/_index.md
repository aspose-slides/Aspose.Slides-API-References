---
title: GetVisualBounds()
second_title: Aspose.Slides for C++ API Reference
description: Gets the visual bounds of the shape calculated from its rendered content.
type: docs
weight: 677
url: /aspose.slides/shape/getvisualbounds/
---
## Shape::GetVisualBounds() method


Gets the visual bounds of the shape calculated from its rendered content.

```cpp
System::Drawing::RectangleF Aspose::Slides::Shape::GetVisualBounds()
```


### Return Value

A [System::Drawing::RectangleF](../../../system.drawing/rectanglef/) that represents the visual bounds of the shape in slide coordinates.
## Remarks


The returned rectangle represents the axis-aligned bounds of all content produced by the shape during rendering in slide coordinate space.

These bounds may differ from the shape's model bounds ([Shape::X](../), [Shape::Y](../), [Shape::Width](../), [Shape::Height](../)) and may contain negative coordinates if the rendered content extends beyond the slide origin.

The visual bounds take into account rendering-related aspects such as transformations (for example, rotation), stroke width and joins, text layout and overflow, [SmartArt](../../../aspose.slides.smartart/) geometry, and other layout effects that influence the final rendered appearance of the shape.

The returned bounds are not clipped to the slide rectangle. 

## See Also

* Class [RectangleF](../../../system.drawing/rectanglef/)
* Class [Shape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)