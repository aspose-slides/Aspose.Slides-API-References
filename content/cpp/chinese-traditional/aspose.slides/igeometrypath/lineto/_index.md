---
title: LineTo()
second_title: Aspose.Slides C++ API 參考
description: 在路徑的末端加入線段
type: docs
weight: 79
url: /zh-hant/aspose.slides/igeometrypath/lineto/
---
## IGeometryPath::LineTo(System::Drawing::PointF) 方法


在路徑的末端加入線段

```cpp
virtual void Aspose::Slides::IGeometryPath::LineTo(System::Drawing::PointF point)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| point | [System::Drawing::PointF](../../../system.drawing/pointf/) | 線段的終點 |

## IGeometryPath::LineTo(float, float) 方法


在路徑的末端加入線段

```cpp
virtual void Aspose::Slides::IGeometryPath::LineTo(float x, float y)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 線段終點的 X 座標 |
| y | **float** | 線段終點的 Y 座標 |

## IGeometryPath::LineTo(System::Drawing::PointF, uint32_t) 方法


在路徑的指定位置加入線段

```cpp
virtual void Aspose::Slides::IGeometryPath::LineTo(System::Drawing::PointF point, uint32_t index)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| point | [System::Drawing::PointF](../../../system.drawing/pointf/) | 終點 |
| index | **uint32_t** | PathData 中段的索引 |

## IGeometryPath::LineTo(float, float, uint32_t) 方法


在路徑的指定位置加入線段

```cpp
virtual void Aspose::Slides::IGeometryPath::LineTo(float x, float y, uint32_t index)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 點的 X 座標 |
| y | **float** | 點的 Y 座標 |
| index | **uint32_t** | PathData 中段的索引 |

## 另請參閱

* 類別 [PointF](../../../system.drawing/pointf/)
* 類別 [IGeometryPath](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)