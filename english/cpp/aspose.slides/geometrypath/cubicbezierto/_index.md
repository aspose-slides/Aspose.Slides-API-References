---
title: CubicBezierTo()
second_title: Aspose.Slides for C++ API Reference
description: Adds cubic Bezier curve at the end the path
type: docs
weight: 105
url: /cpp/aspose.slides/geometrypath/cubicbezierto/
---
## GeometryPath::CubicBezierTo(System::Drawing::PointF, System::Drawing::PointF, System::Drawing::PointF) method


Adds cubic Bezier curve at the end the path

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, System::Drawing::PointF point3) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | First direction point |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Second direction point |
| point3 | [System::Drawing::PointF](../../../system.drawing/pointf/) | End point |

## GeometryPath::CubicBezierTo(float, float, float, float, float, float) method


Adds cubic Bezier curve at the end the path

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x1 | **float** | X coordinate of first direction point |
| y1 | **float** | Y coordinate of first direction point |
| x2 | **float** | X coordinate of second direction point |
| y2 | **float** | Y coordinate of second direction point |
| x3 | **float** | X coordinate of end point |
| y3 | **float** | Y coordinate of end point |

## GeometryPath::CubicBezierTo(System::Drawing::PointF, System::Drawing::PointF, System::Drawing::PointF, uint32_t) method


Adds cubic Bezier curve to the specified place of the path

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, System::Drawing::PointF point3, uint32_t index) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | First direction point |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Second direction point |
| point3 | [System::Drawing::PointF](../../../system.drawing/pointf/) | End point |
| index | **uint32_t** | Index of segment in PathData |

## GeometryPath::CubicBezierTo(float, float, float, float, float, float, uint32_t) method


Adds cubic Bezier curve to the specified place of the path

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, uint32_t index) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x1 | **float** | X coordinate of first direction point |
| y1 | **float** | Y coordinate of first direction point |
| x2 | **float** | X coordinate of second direction point |
| y2 | **float** | Y coordinate of second direction point |
| x3 | **float** | X coordinate of end point |
| y3 | **float** | Y coordinate of end point |
| index | **uint32_t** | Index of segment in PathData |

## See Also

* Class [PointF](../../../system.drawing/pointf/)
* Class [GeometryPath](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)