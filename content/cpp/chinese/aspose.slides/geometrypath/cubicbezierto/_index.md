---
title: CubicBezierTo()
second_title: Aspose.Slides for C++ API 参考
description: 在路径末尾添加三次贝塞尔曲线
type: docs
weight: 105
url: /zh/aspose.slides/geometrypath/cubicbezierto/
---
## GeometryPath::CubicBezierTo(System::Drawing::PointF, System::Drawing::PointF, System::Drawing::PointF) 方法

在路径末尾添加三次贝塞尔曲线

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, System::Drawing::PointF point3) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 第一个方向点 |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 第二个方向点 |
| point3 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 结束点 |

## GeometryPath::CubicBezierTo(float, float, float, float, float, float) 方法

在路径末尾添加三次贝塞尔曲线

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x1 | **float** | 第一个方向点的 X 坐标 |
| y1 | **float** | 第一个方向点的 Y 坐标 |
| x2 | **float** | 第二个方向点的 X 坐标 |
| y2 | **float** | 第二个方向点的 Y 坐标 |
| x3 | **float** | 结束点的 X 坐标 |
| y3 | **float** | 结束点的 Y 坐标 |

## GeometryPath::CubicBezierTo(System::Drawing::PointF, System::Drawing::PointF, System::Drawing::PointF, uint32_t) 方法

在路径的指定位置添加三次贝塞尔曲线

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, System::Drawing::PointF point3, uint32_t index) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 第一个方向点 |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 第二个方向点 |
| point3 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 结束点 |
| index | **uint32_t** | PathData 中段的索引 |

## GeometryPath::CubicBezierTo(float, float, float, float, float, float, uint32_t) 方法

在路径的指定位置添加三次贝塞尔曲线

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, uint32_t index) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x1 | **float** | 第一个方向点的 X 坐标 |
| y1 | **float** | 第一个方向点的 Y 坐标 |
| x2 | **float** | 第二个方向点的 X 坐标 |
| y2 | **float** | 第二个方向点的 Y 坐标 |
| x3 | **float** | 结束点的 X 坐标 |
| y3 | **float** | 结束点的 Y 坐标 |
| index | **uint32_t** | PathData 中段的索引 |

## 另见

* 类 [PointF](../../../system.drawing/pointf/)
* 类 [GeometryPath](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)