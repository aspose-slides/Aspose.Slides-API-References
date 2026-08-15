---
title: QuadraticBezierTo()
second_title: Aspose.Slides for C++ API 參考
description: 在路徑末端添加二次貝茲曲線
type: docs
weight: 105
url: /zh-hant/aspose.slides/igeometrypath/quadraticbezierto/
---
## IGeometryPath::QuadraticBezierTo(System::Drawing::PointF, System::Drawing::PointF) 方法

在路徑末端添加二次貝茲曲線

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 方向點 |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 終點 |

## IGeometryPath::QuadraticBezierTo(float, float, float, float) 方法

在路徑末端添加二次貝茲曲線

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(float x1, float y1, float x2, float y2)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| x1 | **float** | 方向點的 X 座標 |
| y1 | **float** | 方向點的 Y 座標 |
| x2 | **float** | 終點的 X 座標 |
| y2 | **float** | 終點的 Y 座標 |

## IGeometryPath::QuadraticBezierTo(System::Drawing::PointF, System::Drawing::PointF, uint32_t) 方法

在路徑的指定位置添加二次貝茲曲線

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, uint32_t index)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 方向點 |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 終點 |
| index | **uint32_t** | PathData 中段的索引 |

## IGeometryPath::QuadraticBezierTo(float, float, float, float, uint32_t) 方法

在路徑的指定位置添加二次貝茲曲線

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(float x1, float y1, float x2, float y2, uint32_t index)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| x1 | **float** | 方向點的 X 座標 |
| y1 | **float** | 方向點的 Y 座標 |
| x2 | **float** | 終點的 X 座標 |
| y2 | **float** | 終點的 Y 座標 |
| index | **uint32_t** | PathData 中段的索引 |

## 參見

* 類別 [PointF](../../../system.drawing/pointf/)
* 類別 [IGeometryPath](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)