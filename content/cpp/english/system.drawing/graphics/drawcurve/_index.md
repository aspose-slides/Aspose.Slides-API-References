---
title: DrawCurve()
second_title: Aspose.Slides for C++ API Reference
description: Draws a spline using the specified pen.
type: docs
weight: 794
url: /system.drawing/graphics/drawcurve/
---
## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float) method


Draws a spline using the specified pen.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | A pen to use when drawing the spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) of points that determines the spline |
| tension | **float** | Value that specifies the tension of the spline |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float) method


Draws a spline using the specified pen.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | A pen to use when drawing the spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) of points that determines the spline |
| tension | **float** | Value that specifies the tension of the spline |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, int32_t, int32_t, float) method


Draws a spline using the specified pen.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | A pen to use when drawing the spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) of points that determines the spline |
| offset | **int32_t** | Offset from the 1st element in the **points** array |
| numberOfSegments | **int32_t** | Number of segments to include into the curve |
| tension | **float** | Value that specifies the tension of the spline |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, int32_t, int32_t, float) method


Draws a spline using the specified pen.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | A pen to use when drawing the spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) of points that determines the spline |
| offset | **int32_t** | Offset from the 1st element in the **points** array |
| numberOfSegments | **int32_t** | Number of segments to include into the curve |
| tension | **float** | Value that specifies the tension of the spline |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Pen](../../pen/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)