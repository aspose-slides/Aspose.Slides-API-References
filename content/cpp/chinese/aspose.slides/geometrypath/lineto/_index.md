---
title: LineTo()
second_title: Aspose.Slides C++ API 参考
description: 在路径末尾添加线段
type: docs
weight: 92
url: /zh/aspose.slides/geometrypath/lineto/
---
## GeometryPath::LineTo(System::Drawing::PointF) 方法

在路径末尾添加线段

```cpp
void Aspose::Slides::GeometryPath::LineTo(System::Drawing::PointF point) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [System::Drawing::PointF](../../../system.drawing/pointf/) | 线段的终点 |

## GeometryPath::LineTo(float, float) 方法

在路径末尾添加线段

```cpp
void Aspose::Slides::GeometryPath::LineTo(float x, float y) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 线段终点的 X 坐标 |
| y | **float** | 线段终点的 Y 坐标 |

## GeometryPath::LineTo(System::Drawing::PointF, uint32_t) 方法

在路径的指定位置添加线段

```cpp
void Aspose::Slides::GeometryPath::LineTo(System::Drawing::PointF point, uint32_t index) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [System::Drawing::PointF](../../../system.drawing/pointf/) | 终点 |
| index | **uint32_t** | PathData 中段的索引 |

## GeometryPath::LineTo(float, float, uint32_t) 方法

在路径的指定位置添加线段

```cpp
void Aspose::Slides::GeometryPath::LineTo(float x, float y, uint32_t index) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 点的 X 坐标 |
| y | **float** | 点的 Y 坐标 |
| index | **uint32_t** | PathData 中段的索引 |

## 另见

* 类 [PointF](../../../system.drawing/pointf/)
* 类 [GeometryPath](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)