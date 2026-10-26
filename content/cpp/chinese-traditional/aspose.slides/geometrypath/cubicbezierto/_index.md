---
title: CubicBezierTo()
second_title: Aspose.Slides for C++ API 參考
description: 在路徑末端添加三次貝茲曲線
type: docs
weight: 105
url: /zh-hant/aspose.slides/geometrypath/cubicbezierto/
---
## GeometryPath::CubicBezierTo(System::Drawing::PointF, System::Drawing::PointF, System::Drawing::PointF) method


在路徑末端添加三次貝茲曲線

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, System::Drawing::PointF point3) override
```


### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | First direction point |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Second direction point |
| point3 | [System::Drawing::PointF](../../../system.drawing/pointf/) | End point |

## GeometryPath::CubicBezierTo(float, float, float, float, float, float) method


在路徑末端添加三次貝茲曲線

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) override
```


### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| x1 | **float** | X coordinate of first direction point |
| y1 | **float** | Y coordinate of first direction point |
| x2 | **float** | X coordinate of second direction point |
| y2 | **float** | Y coordinate of second direction point |
| x3 | **float** | X coordinate of end point |
| y3 | **float** | Y coordinate of end point |

## GeometryPath::CubicBezierTo(System::Drawing::PointF, System::Drawing::PointF, System::Drawing::PointF, uint32_t) method


在路徑指定位置添加三次貝茲曲線

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, System::Drawing::PointF point3, uint32_t index) override
```


### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | First direction point |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | Second direction point |
| point3 | [System::Drawing::PointF](../../../system.drawing/pointf/) | End point |
| index | **uint32_t** | Index of segment in PathData |

## GeometryPath::CubicBezierTo(float, float, float, float, float, float, uint32_t) method


在路徑指定位置添加三次貝茲曲線

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, uint32_t index) override
```


### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| x1 | **float** | X coordinate of first direction point |
| y1 | **float** | Y coordinate of first direction point |
| x2 | **float** | X coordinate of second direction point |
| y2 | **float** | Y coordinate of second direction point |
| x3 | **float** | X coordinate of end point |
| y3 | **float** | Y coordinate of end point |
| index | **uint32_t** | Index of segment in PathData |

## 另請參閱

* 類別 [PointF](../../../system.drawing/pointf/)
* 類別 [GeometryPath](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)