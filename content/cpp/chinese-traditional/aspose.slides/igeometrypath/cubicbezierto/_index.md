---
title: CubicBezierTo()
second_title: Aspose.Slides for C++ API 參考
description: 在路徑末端添加立方貝塞爾曲線
type: docs
weight: 92
url: /zh-hant/aspose.slides/igeometrypath/cubicbezierto/
---
## IGeometryPath::CubicBezierTo(System::Drawing::PointF, System::Drawing::PointF, System::Drawing::PointF) 方法

在路徑末端添加立方貝塞爾曲線

```cpp
virtual void Aspose::Slides::IGeometryPath::CubicBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, System::Drawing::PointF point3)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 第一方向點 |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 第二方向點 |
| point3 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 結束點 |

## IGeometryPath::CubicBezierTo(float, float, float, float, float, float) 方法

在路徑末端添加立方貝塞爾曲線

```cpp
virtual void Aspose::Slides::IGeometryPath::CubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| x1 | **float** | 第一方向點的 X 座標 |
| y1 | **float** | 第一方向點的 Y 座標 |
| x2 | **float** | 第二方向點的 X 座標 |
| y2 | **float** | 第二方向點的 Y 座標 |
| x3 | **float** | 結束點的 X 座標 |
| y3 | **float** | 結束點的 Y 座標 |

## IGeometryPath::CubicBezierTo(System::Drawing::PointF, System::Drawing::PointF, System::Drawing::PointF, uint32_t) 方法

在路徑的指定位置添加立方貝塞爾曲線

```cpp
virtual void Aspose::Slides::IGeometryPath::CubicBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, System::Drawing::PointF point3, uint32_t index)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 第一方向點 |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 第二方向點 |
| point3 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 結束點 |
| index | **uint32_t** | PathData 中段的索引 |

## IGeometryPath::CubicBezierTo(float, float, float, float, float, float, uint32_t) 方法

在路徑的指定位置添加立方貝塞爾曲線

```cpp
virtual void Aspose::Slides::IGeometryPath::CubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, uint32_t index)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| x1 | **float** | 第一方向點的 X 座標 |
| y1 | **float** | 第一方向點的 Y 座標 |
| x2 | **float** | 第二方向點的 X 座標 |
| y2 | **float** | 第二方向點的 Y 座標 |
| x3 | **float** | 結束點的 X 座標 |
| y3 | **float** | 結束點的 Y 座標 |
| index | **uint32_t** | PathData 中段的索引 |

## 參見

* 類別 [PointF](../../../system.drawing/pointf/)
* 類別 [IGeometryPath](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)