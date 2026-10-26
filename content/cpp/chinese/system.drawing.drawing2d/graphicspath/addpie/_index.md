---
title: AddPie()
second_title: Aspose.Slides C++ API 参考
description: 将指定的饼形轮廓添加到当前对象表示的路径中。
type: docs
weight: 209
url: /zh/system.drawing.drawing2d/graphicspath/addpie/
---
## GraphicsPath::AddPie(float, float, float, float, float, float) 方法

将指定的饼形轮廓添加到当前对象表示的路径中。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 饼形绘制所在椭圆的外接矩形左上角的 X 坐标 |
| y | **float** | 饼形绘制所在椭圆的外接矩形左上角的 Y 坐标 |
| width | **float** | 饼形绘制所在椭圆的外接矩形左上角的宽度 |
| height | **float** | 饼形绘制所在椭圆的外接矩形左上角的高度 |
| startAngle | **float** | 指定饼形的起始角度（单位：度），相对于 X 轴顺时针测量 |
| sweepAngle | **float** | 指定起始角度与饼形结束之间的角度 |

## GraphicsPath::AddPie(int, int, int, int, float, float) 方法

将指定的饼形轮廓添加到当前对象表示的路径中。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(int x, int y, int width, int height, float startAngle, float sweepAngle)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 饼形绘制所在椭圆的外接矩形左上角的 X 坐标 |
| y | int | 饼形绘制所在椭圆的外接矩形左上角的 Y 坐标 |
| width | int | 饼形绘制所在椭圆的外接矩形左上角的宽度 |
| height | int | 饼形绘制所在椭圆的外接矩形左上角的高度 |
| startAngle | **float** | 指定饼形的起始角度（单位：度），相对于 X 轴顺时针测量 |
| sweepAngle | **float** | 指定起始角度与饼形结束之间的角度 |

## GraphicsPath::AddPie(const Rectangle\&, float, float) 方法

将指定的饼形轮廓添加到当前对象表示的路径中。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(const Rectangle &rect, float startAngle, float sweepAngle)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const [Rectangle](../../../system.drawing/rectangle/)\& | 用于绘制饼形的椭圆的外接矩形 |
| startAngle | **float** | 指定饼形的起始角度（单位：度），相对于 X 轴顺时针测量 |
| sweepAngle | **float** | 指定起始角度与饼形结束之间的角度 |

## 另请参见

* 类 [GraphicsPath](../)
* 类 [Rectangle](../../../system.drawing/rectangle/)
* 命名空间 [System::Drawing::Drawing2D](../../)
* 库 [Aspose.Slides](../../../)