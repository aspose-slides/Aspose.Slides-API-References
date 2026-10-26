---
title: QuadraticBezierTo()
second_title: Aspose.Slides C++ API 参考
description: 在路径的末端添加二次贝塞尔曲线
type: docs
weight: 105
url: /zh/aspose.slides/igeometrypath/quadraticbezierto/
---
## IGeometryPath::QuadraticBezierTo(System::Drawing::PointF, System::Drawing::PointF) 方法

在路径的末端添加二次贝塞尔曲线

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 方向点 |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 结束点 |

## IGeometryPath::QuadraticBezierTo(float, float, float, float) 方法

在路径的末端添加二次贝塞尔曲线

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(float x1, float y1, float x2, float y2)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x1 | **float** | 方向点的 X 坐标 |
| y1 | **float** | 方向点的 Y 坐标 |
| x2 | **float** | 结束点的 X 坐标 |
| y2 | **float** | 结束点的 Y 坐标 |

## IGeometryPath::QuadraticBezierTo(System::Drawing::PointF, System::Drawing::PointF, uint32_t) 方法


在路径的指定位置添加二次贝塞尔曲线

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, uint32_t index)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 方向点 |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 结束点 |
| index | **uint32_t** | PathData 中段的索引 |

## IGeometryPath::QuadraticBezierTo(float, float, float, float, uint32_t) 方法


在路径的指定位置添加二次贝塞尔曲线

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(float x1, float y1, float x2, float y2, uint32_t index)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x1 | **float** | 方向点的 X 坐标 |
| y1 | **float** | 方向点的 Y 坐标 |
| x2 | **float** | 结束点的 X 坐标 |
| y2 | **float** | 结束点的 Y 坐标 |
| index | **uint32_t** | PathData 中段的索引 |

## 另请参见

* 类 [PointF](../../../system.drawing/pointf/)
* 类 [IGeometryPath](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)