---
title: DrawClosedCurve()
second_title: Aspose.Slides for C++ API Reference
description: Draws a closed spline using the specified pen.
type: docs
weight: 781
url: /cpp/system.drawing/graphics/drawclosedcurve/
---
## Graphics::DrawClosedCurve(const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\&, const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\&, **float**, [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/)) method


Draws a closed spline using the specified pen.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | A pen to use when drawing the spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) of points that determines the spline |
| tension | **float** | Value that specifies the tension of the spline |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | IGNORED |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Pen](../../pen/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Point](../../point/)
* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
## Graphics::DrawClosedCurve(const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\&, const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\&, **float**, [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/)) method


Draws a closed spline using the specified pen.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | A pen to use when drawing the spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) of points that determines the spline |
| tension | **float** | Value that specifies the tension of the spline |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | IGNORED |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Pen](../../pen/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PointF](../../pointf/)
* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
