---
title: QuadraticBezierTo()
second_title: Aspose.Slides for C++ API 参考
description: 在路径末尾添加二次贝塞尔曲线
type: docs
weight: 118
url: /zh/aspose.slides/geometrypath/quadraticbezierto/
---
## GeometryPath::QuadraticBezierTo(System::Drawing::PointF, System::Drawing::PointF) 方法

在路径末尾添加二次贝塞尔曲线

```cpp
void Aspose::Slides::GeometryPath::QuadraticBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 方向点 |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 结束点 |

## GeometryPath::QuadraticBezierTo(float, float, float, float) 方法

在路径末尾添加二次贝塞尔曲线

```cpp
void Aspose::Slides::GeometryPath::QuadraticBezierTo(float x1, float y1, float x2, float y2) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x1 | **float** | 方向点的 X 坐标 |
| y1 | **float** | 方向点的 Y 坐标 |
| x2 | **float** | 结束点的 X 坐标 |
| y2 | **float** | 结束点的 Y 坐标 |

## GeometryPath::QuadraticBezierTo(System::Drawing::PointF, System::Drawing::PointF, uint32_t) 方法

在路径的指定位置添加二次贝塞尔曲线

```cpp
void Aspose::Slides::GeometryPath::QuadraticBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, uint32_t index) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 方向点 |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 结束点 |
| index | **uint32_t** | PathData 中段的索引 |

## GeometryPath::QuadraticBezierTo(float, float, float, float, uint32_t) 方法

在路径的指定位置添加二次贝塞尔曲线

```cpp
void Aspose::Slides::GeometryPath::QuadraticBezierTo(float x1, float y1, float x2, float y2, uint32_t index) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x1 | **float** | 方向点的 X 坐标 |
| y1 | **float** | 方向点的 Y 坐标 |
| x2 | **float** | 结束点的 X 坐标 |
| y2 | **float** | 结束点的 Y 坐标 |
| index | **uint32_t** | PathData 中段的索引 |

## 另请参阅

* 类 [PointF](../../../system.drawing/pointf/)
* 类 [GeometryPath](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)