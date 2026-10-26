---
title: DrawPie()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的笔在当前对象表示的表面上绘制指定的饼形。
type: docs
weight: 261
url: /zh/system.drawing/graphics/drawpie/
---
## Graphics::DrawPie(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) method

使用指定的笔在当前对象表示的表面上绘制指定的饼形。

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 用于绘制饼形的笔 |
| x | **int32_t** | 定义椭圆的矩形左上角的 X 坐标 |
| y | **int32_t** | 定义椭圆的矩形左上角的 Y 坐标 |
| width | **int32_t** | 定义椭圆的矩形的宽度 |
| height | **int32_t** | 定义椭圆的矩形的高度 |
| startAngle | **int32_t** | 从 X 轴顺时针测量到饼形起始点的角度（度） |
| sweepAngle | **int32_t** | 从 **startAngle** 顺时针测量到饼形结束点的角度（度） |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) method

使用指定的笔在当前对象表示的表面上绘制指定的饼形。

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 用于绘制饼形的笔 |
| x | **float** | 定义椭圆的矩形左上角的 X 坐标 |
| y | **float** | 定义椭圆的矩形左上角的 Y 坐标 |
| width | **float** | 定义椭圆的矩形的宽度 |
| height | **float** | 定义椭圆的矩形的高度 |
| startAngle | **float** | 从 X 轴顺时针测量到饼形起始点的角度（度） |
| sweepAngle | **float** | 从 **startAngle** 顺时针测量到饼形结束点的角度（度） |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, Rectangle, float, float) method

使用指定的笔在当前对象表示的表面上绘制指定的饼形。

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 用于绘制饼形的笔 |
| rect | [Rectangle](../../rectangle/) | 定义椭圆的矩形 |
| startAngle | **float** | 从 X 轴顺时针测量到饼形起始点的角度（度） |
| sweepAngle | **float** | 从 **startAngle** 顺时针测量到饼形结束点的角度（度） |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, RectangleF, float, float) method

使用指定的笔在当前对象表示的表面上绘制指定的饼形。

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 用于绘制饼形的笔 |
| rect | [RectangleF](../../rectanglef/) | 定义椭圆的矩形 |
| startAngle | **float** | 从 X 轴顺时针测量到饼形起始点的角度（度） |
| sweepAngle | **float** | 从 **startAngle** 顺时针测量到饼形结束点的角度（度） |

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Pen](../../pen/)
* 类 [Graphics](../)
* 类 [Rectangle](../../rectangle/)
* 类 [RectangleF](../../rectanglef/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)