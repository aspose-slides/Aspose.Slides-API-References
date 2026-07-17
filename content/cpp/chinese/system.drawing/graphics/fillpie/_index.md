---
title: FillPie()
second_title: Aspose.Slides C++ API 参考
description: 使用指定的画刷在当前对象表示的表面上填充指定的饼形。
type: docs
weight: 274
url: /zh/system.drawing/graphics/fillpie/
---
## Graphics::FillPie(const SharedPtr\<Brush\>\&, int, int, int, int, int, int) 方法

使用指定的画刷在当前对象表示的表面上填充指定的饼形。

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 填充饼形时使用的画刷 |
| x | int | 定义椭圆的矩形左上角的X坐标 |
| y | int | 定义椭圆的矩形左上角的Y坐标 |
| width | int | 定义椭圆的矩形的宽度 |
| height | int | 定义椭圆的矩形的高度 |
| startAngle | int | 从X轴顺时针测量至饼形起始点的角度（度） |
| sweepAngle | int | 从**startAngle**顺时针测量至饼形结束点的角度（度） |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, float, float, float, float, float, float) 方法

使用指定的画刷在当前对象表示的表面上填充指定的饼形。

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 填充饼形时使用的画刷 |
| x | **float** | 定义椭圆的矩形左上角的X坐标 |
| y | **float** | 定义椭圆的矩形左上角的Y坐标 |
| width | **float** | 定义椭圆的矩形的宽度 |
| height | **float** | 定义椭圆的矩形的高度 |
| startAngle | **float** | 从X轴顺时针测量至饼形起始点的角度（度） |
| sweepAngle | **float** | 从**startAngle**顺时针测量至饼形结束点的角度（度） |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, Rectangle, float, float) 方法

使用指定的画刷在当前对象表示的表面上填充指定的饼形。

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, Rectangle rect, float startAngle, float sweepAngle)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 填充饼形时使用的画刷 |
| rect | [Rectangle](../../rectangle/) | 定义椭圆的矩形 |
| startAngle | **float** | 从X轴顺时针测量至饼形起始点的角度（度） |
| sweepAngle | **float** | 从**startAngle**顺时针测量至饼形结束点的角度（度） |

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Brush](../../brush/)
* 类 [Graphics](../)
* 类 [Rectangle](../../rectangle/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)