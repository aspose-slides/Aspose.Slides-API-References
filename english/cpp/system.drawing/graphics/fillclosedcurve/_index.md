---
title: FillClosedCurve()
second_title: Aspose.Slides for C++ API Reference
description: Draws a closed spline using the specified brush.
type: docs
weight: 807
url: /cpp/system.drawing/graphics/fillclosedcurve/
---
## Graphics::FillClosedCurve(const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\&, const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\&, [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/), **float**) method


Draws a closed spline using the specified brush.

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | A brush to use when drawing the spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) of points that determines the spline |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | IGNORED |
| tension | **float** | Value that specifies the tension of the spline |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Brush](../../brush/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PointF](../../pointf/)
* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
## Graphics::FillClosedCurve(const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\&, const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\&, [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/), **float**) method


Draws a closed spline using the specified brush.

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | A brush to use when drawing the spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) of points that determines the spline |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | IGNORED |
| tension | **float** | Value that specifies the tension of the spline |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Brush](../../brush/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Point](../../point/)
* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
