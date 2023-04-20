---
title: GeometryPathToGraphicsPath()
second_title: Aspose.Slides for C++ API Reference
description: "Converts IGeometryPath to System::Drawing::Drawing2D::GraphicsPath."
type: docs
weight: 14
url: /cpp/aspose.slides.util/shapeutil/geometrypathtographicspath/
---
## ShapeUtil::GeometryPathToGraphicsPath(System::SharedPtr\<IGeometryPath\>) method


Converts [IGeometryPath](../../../aspose.slides/igeometrypath/) to [System::Drawing::Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/).

```cpp
static System::SharedPtr<System::Drawing::Drawing2D::GraphicsPath> Aspose::Slides::Util::ShapeUtil::GeometryPathToGraphicsPath(System::SharedPtr<IGeometryPath> geometryPath)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| geometryPath | [System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../../aspose.slides/igeometrypath/)\> |  |

### Return Value

Graphics path
## Remarks


GraphicsPath can be transformed in a different ways using its convenient methods and then transformed back into the [IGeometryPath](../../../aspose.slides/igeometrypath/) to use in [GeometryShape](../../../aspose.slides/geometryshape/) via [ShapeUtil::GraphicsPathToGeometryPath](../graphicspathtogeometrypath/) method. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Class [IGeometryPath](../../../aspose.slides/igeometrypath/)
* Class [ShapeUtil](../)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)