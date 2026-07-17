---
title: AddCurve()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的曲线添加到当前对象表示的路径中。
type: docs
weight: 274
url: /zh/system.drawing.drawing2d/graphicspath/addcurve/
---
## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, float) 方法

将指定的曲线添加到当前对象表示的路径中。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, float tension=0.5)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | 指定曲线的点 |
| tension | **float** | 指定曲线在控制点之间的弯曲程度 |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, float) 方法

将指定的曲线添加到当前对象表示的路径中。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, float tension=0.5)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | 指定曲线的点 |
| tension | **float** | 指定曲线在控制点之间的弯曲程度 |

## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, int, int, float) 方法

将指定的曲线添加到当前对象表示的路径中。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, int offset, int number_of_segments, float tension)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | 指定曲线的点 |
| offset | int | **points** 中用作曲线起始点的索引 |
| number_of_segments | int | 用于绘制曲线的段数 |
| tension | **float** | 指定曲线在控制点之间的弯曲程度 |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, int, int, float) 方法

将指定的曲线添加到当前对象表示的路径中。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, int offset, int number_of_segments, float tension)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | 指定曲线的点 |
| offset | int | **points** 中用作曲线起始点的索引 |
| number_of_segments | int | 用于绘制曲线的段数 |
| tension | **float** | 指定曲线在控制点之间的弯曲程度 |

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [PointF](../../../system.drawing/pointf/)
* 类 [GraphicsPath](../)
* 类 [Point](../../../system.drawing/point/)
* 命名空间 [System::Drawing::Drawing2D](../../)
* 库 [Aspose.Slides](../../../)