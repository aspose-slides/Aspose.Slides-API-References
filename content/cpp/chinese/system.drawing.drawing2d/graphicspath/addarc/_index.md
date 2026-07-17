---
title: AddArc()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的椭圆弧添加到当前对象表示的路径中。
type: docs
weight: 183
url: /zh/system.drawing.drawing2d/graphicspath/addarc/
---
## GraphicsPath::AddArc(float, float, float, float, float, float) 方法

将指定的椭圆弧添加到当前对象表示的路径中。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 椭圆所在矩形左上角的 X 坐标 |
| y | **float** | 椭圆所在矩形左上角的 Y 坐标 |
| width | **float** | 椭圆所在矩形左上角的宽度 |
| height | **float** | 椭圆所在矩形左上角的高度 |
| startAngle | **float** | 指定弧线的起始角度（以度为单位），顺时针从 X 轴测量 |
| sweepAngle | **float** | 指定起始角度与弧线结束之间的角度 |

## GraphicsPath::AddArc(int, int, int, int, float, float) 方法

将指定的椭圆弧添加到当前对象表示的路径中。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(int x, int y, int width, int height, float startAngle, float sweepAngle)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 椭圆所在矩形左上角的 X 坐标 |
| y | int | 椭圆所在矩形左上角的 Y 坐标 |
| width | int | 椭圆所在矩形左上角的宽度 |
| height | int | 椭圆所在矩形左上角的高度 |
| startAngle | **float** | 指定弧线的起始角度（以度为单位），顺时针从 X 轴测量 |
| sweepAngle | **float** | 指定起始角度与弧线结束之间的角度 |

## GraphicsPath::AddArc(const RectangleF\&, float, float) 方法

将指定的椭圆弧添加到当前对象表示的路径中。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(const RectangleF &rect, float startAngle, float sweepAngle)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const [RectangleF](../../../system.drawing/rectanglef/)\& | 包围弧线所在椭圆的矩形 |
| startAngle | **float** | 指定弧线的起始角度（以度为单位），顺时针从 X 轴测量 |
| sweepAngle | **float** | 指定起始角度与弧线结束之间的角度 |

## GraphicsPath::AddArc(const Rectangle\&, float, float) 方法

将指定的椭圆弧添加到当前对象表示的路径中。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(const Rectangle &rect, float startAngle, float sweepAngle)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const [Rectangle](../../../system.drawing/rectangle/)\& | 包围弧线所在椭圆的矩形 |
| startAngle | **float** | 指定弧线的起始角度（以度为单位），顺时针从 X 轴测量 |
| sweepAngle | **float** | 指定起始角度与弧线结束之间的角度 |

## 另见

* 类 [GraphicsPath](../)
* 类 [RectangleF](../../../system.drawing/rectanglef/)
* 类 [Rectangle](../../../system.drawing/rectangle/)
* 命名空间 [System::Drawing::Drawing2D](../../)
* 库 [Aspose.Slides](../../../)