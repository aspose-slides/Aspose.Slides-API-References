---
title: LineTo()
second_title: Aspose.Slides for C++ API Reference
description: Adds line to the end of the path
type: docs
weight: 92
url: /aspose.slides/geometrypath/lineto/
---
## GeometryPath::LineTo(System::Drawing::PointF) method


Adds line to the end of the path

```cpp
void Aspose::Slides::GeometryPath::LineTo(System::Drawing::PointF point) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| point | [System::Drawing::PointF](../../../system.drawing/pointf/) | End point of the line |

## GeometryPath::LineTo(float, float) method


Adds line to the end of the path

```cpp
void Aspose::Slides::GeometryPath::LineTo(float x, float y) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | X coordinate of the end point of the line |
| y | **float** | Y coordinate of the end point of the line |

## GeometryPath::LineTo(System::Drawing::PointF, uint32_t) method


Adds line to the specified place of the path

```cpp
void Aspose::Slides::GeometryPath::LineTo(System::Drawing::PointF point, uint32_t index) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| point | [System::Drawing::PointF](../../../system.drawing/pointf/) | End point |
| index | **uint32_t** | Index of segment in PathData |

## GeometryPath::LineTo(float, float, uint32_t) method


Adds line to the specified place of the path

```cpp
void Aspose::Slides::GeometryPath::LineTo(float x, float y, uint32_t index) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | X coordinate of the point |
| y | **float** | Y coordinate of the point |
| index | **uint32_t** | Index of segment in PathData |

## See Also

* Class [PointF](../../../system.drawing/pointf/)
* Class [GeometryPath](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)