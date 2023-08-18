---
title: FillPolygon()
second_title: Aspose.Slides for C++ API Reference
description: Fills the interiors of the specified polygon using the specified brush.
type: docs
weight: 417
url: /system.drawing/graphics/fillpolygon/
---
## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode) method


Fills the interiors of the specified polygon using the specified brush.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | A [Brush](../../brush/) object that specifies the parameters of the fill |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | An array containing the points that define the polygon |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | The fill mode |

## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode) method


Fills the interiors of the specified polygon using the specified brush.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | A [Brush](../../brush/) object that specifies the parameters of the fill |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | An array containing the points that define the polygon |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | The fill mode |

## See Also

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Brush](../../brush/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)