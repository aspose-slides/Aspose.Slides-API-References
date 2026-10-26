---
title: LineTo()
second_title: Aspose.Slides C++ API 参考
description: 在路径末尾添加直线
type: docs
weight: 79
url: /zh/aspose.slides/igeometrypath/lineto/
---
## IGeometryPath::LineTo(System::Drawing::PointF) 方法

在路径末尾添加直线

```cpp
virtual void Aspose::Slides::IGeometryPath::LineTo(System::Drawing::PointF point)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [System::Drawing::PointF](../../../system.drawing/pointf/) | 直线的终点 |

## IGeometryPath::LineTo(float, float) 方法

在路径末尾添加直线

```cpp
virtual void Aspose::Slides::IGeometryPath::LineTo(float x, float y)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 直线终点的 X 坐标 |
| y | **float** | 直线终点的 Y 坐标 |

## IGeometryPath::LineTo(System::Drawing::PointF, uint32_t) 方法

在路径的指定位置添加直线

```cpp
virtual void Aspose::Slides::IGeometryPath::LineTo(System::Drawing::PointF point, uint32_t index)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | [System::Drawing::PointF](../../../system.drawing/pointf/) | 终点 |
| index | **uint32_t** | PathData 中段的索引 |

## IGeometryPath::LineTo(float, float, uint32_t) 方法

在路径的指定位置添加直线

```cpp
virtual void Aspose::Slides::IGeometryPath::LineTo(float x, float y, uint32_t index)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 点的 X 坐标 |
| y | **float** | 点的 Y 坐标 |
| index | **uint32_t** | PathData 中段的索引 |

## 另请参见

* 类 [PointF](../../../system.drawing/pointf/)
* 类 [IGeometryPath](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)