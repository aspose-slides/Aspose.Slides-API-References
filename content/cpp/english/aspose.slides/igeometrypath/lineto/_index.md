---
title: LineTo()
second_title: Aspose.Slides for C++ API Reference
description: Adds line to the end of the path
type: docs
weight: 79
url: /aspose.slides/igeometrypath/lineto/
---
## IGeometryPath::LineTo(System::Drawing::PointF) method


Adds line to the end of the path

```cpp
virtual void Aspose::Slides::IGeometryPath::LineTo(System::Drawing::PointF point)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| point | [System::Drawing::PointF](../../../system.drawing/pointf/) | End point of the line |

## IGeometryPath::LineTo(float, float) method


Adds line to the end of the path

```cpp
virtual void Aspose::Slides::IGeometryPath::LineTo(float x, float y)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | X coordinate of the end point of the line |
| y | **float** | Y coordinate of the end point of the line |

## IGeometryPath::LineTo(System::Drawing::PointF, uint32_t) method


Adds line to the specified place of the path

```cpp
virtual void Aspose::Slides::IGeometryPath::LineTo(System::Drawing::PointF point, uint32_t index)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| point | [System::Drawing::PointF](../../../system.drawing/pointf/) | End point |
| index | **uint32_t** | Index of segment in PathData |

## IGeometryPath::LineTo(float, float, uint32_t) method


Adds line to the specified place of the path

```cpp
virtual void Aspose::Slides::IGeometryPath::LineTo(float x, float y, uint32_t index)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | X coordinate of the point |
| y | **float** | Y coordinate of the point |
| index | **uint32_t** | Index of segment in PathData |

## See Also

* Class [PointF](../../../system.drawing/pointf/)
* Class [IGeometryPath](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)