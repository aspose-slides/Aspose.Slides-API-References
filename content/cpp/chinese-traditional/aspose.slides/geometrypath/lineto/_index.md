---
title: LineTo()
second_title: Aspose.Slides for C++ API 參考
description: 在路徑的末端加入線段
type: docs
weight: 92
url: /zh-hant/aspose.slides/geometrypath/lineto/
---
## GeometryPath::LineTo(System::Drawing::PointF) 方法

在路徑的末端加入線段

```cpp
void Aspose::Slides::GeometryPath::LineTo(System::Drawing::PointF point) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| point | [System::Drawing::PointF](../../../system.drawing/pointf/) | 線段的終點 |

## GeometryPath::LineTo(float, float) 方法

在路徑的末端加入線段

```cpp
void Aspose::Slides::GeometryPath::LineTo(float x, float y) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | **float** | 線段終點的 X 座標 |
| y | **float** | 線段終點的 Y 座標 |

## GeometryPath::LineTo(System::Drawing::PointF, uint32_t) 方法

在路徑的指定位置加入線段

```cpp
void Aspose::Slides::GeometryPath::LineTo(System::Drawing::PointF point, uint32_t index) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| point | [System::Drawing::PointF](../../../system.drawing/pointf/) | 終點 |
| index | **uint32_t** | PathData 中段的索引 |

## GeometryPath::LineTo(float, float, uint32_t) 方法

在路徑的指定位置加入線段

```cpp
void Aspose::Slides::GeometryPath::LineTo(float x, float y, uint32_t index) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | **float** | 點的 X 座標 |
| y | **float** | 點的 Y 座標 |
| index | **uint32_t** | PathData 中段的索引 |

## 另請參閱

* 類別 [PointF](../../../system.drawing/pointf/)
* 類別 [GeometryPath](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)