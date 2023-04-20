---
title: QuadraticBezierTo()
second_title: Aspose.Slides for C++ API Reference
description: Adds quadratic Bezier curve at the end the path
type: docs
weight: 118
url: /cpp/aspose.slides/geometrypath/quadraticbezierto/
---
## GeometryPath::QuadraticBezierTo(System::Drawing::PointF, System::Drawing::PointF) method


Adds quadratic Bezier curve at the end the path

```cpp
void Aspose::Slides::GeometryPath::QuadraticBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Direction point |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | End point |

## GeometryPath::QuadraticBezierTo(float, float, float, float) method


Adds quadratic Bezier curve at the end the path

```cpp
void Aspose::Slides::GeometryPath::QuadraticBezierTo(float x1, float y1, float x2, float y2) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x1 | **float** | X coordinate of direction point |
| y1 | **float** | Y coordinate of direction point |
| x2 | **float** | X coordinate of end point |
| y2 | **float** | Y coordinate of end point |

## GeometryPath::QuadraticBezierTo(System::Drawing::PointF, System::Drawing::PointF, uint32_t) method


Adds quadratic Bezier curve to the specified place of the path

```cpp
void Aspose::Slides::GeometryPath::QuadraticBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, uint32_t index) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Direction point |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | End point |
| index | **uint32_t** | Index of segment in PathData |

## GeometryPath::QuadraticBezierTo(float, float, float, float, uint32_t) method


Adds quadratic Bezier curve to the specified place of the path

```cpp
void Aspose::Slides::GeometryPath::QuadraticBezierTo(float x1, float y1, float x2, float y2, uint32_t index) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x1 | **float** | X coordinate of direction point |
| y1 | **float** | Y coordinate of direction point |
| x2 | **float** | X coordinate of end point |
| y2 | **float** | Y coordinate of end point |
| index | **uint32_t** | Index of segment in PathData |

## See Also

* Class [PointF](../../../system.drawing/pointf/)
* Class [GeometryPath](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)