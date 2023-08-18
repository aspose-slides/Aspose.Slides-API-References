---
title: PathGradientBrush()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance of PathGradientBrush class.
type: docs
weight: 1
url: /system.drawing.drawing2d/pathgradientbrush/pathgradientbrush/
---
## PathGradientBrush::PathGradientBrush(const ArrayPtr\<PointF\>\&, WrapMode) constructor


Constructs a new instance of [PathGradientBrush](../) class.

```cpp
System::Drawing::Drawing2D::PathGradientBrush::PathGradientBrush(const ArrayPtr<PointF> &points, WrapMode wrapMode=WrapMode::Clamp)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | An array that contains vertices of the path |
| wrapMode | [WrapMode](../../wrapmode/) | Specifies how the fills drawn by a brush represented by the object being created should be tiled |

## PathGradientBrush::PathGradientBrush(const ArrayPtr\<Point\>\&, WrapMode) constructor


Constructs a new instance of [PathGradientBrush](../) class.

```cpp
System::Drawing::Drawing2D::PathGradientBrush::PathGradientBrush(const ArrayPtr<Point> &points, WrapMode wrapMode=WrapMode::Clamp)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | An array that contains vertices of the path |
| wrapMode | [WrapMode](../../wrapmode/) | Specifies how the fills drawn by a brush represented by the object being created should be tiled |

## PathGradientBrush::PathGradientBrush(const SharedPtr\<GraphicsPath\>\&) constructor


Constructs a new instance of [PathGradientBrush](../) class.

```cpp
System::Drawing::Drawing2D::PathGradientBrush::PathGradientBrush(const SharedPtr<GraphicsPath> &path)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | A [GraphicsPath](../../graphicspath/) object that specifies a path filled by the object being created |

## See Also

* Enum [WrapMode](../../wrapmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [PathGradientBrush](../)
* Class [Point](../../../system.drawing/point/)
* Class [GraphicsPath](../../graphicspath/)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)