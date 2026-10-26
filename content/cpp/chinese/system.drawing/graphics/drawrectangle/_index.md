---
title: DrawRectangle()
second_title: Aspose.Slides for C++ API 参考
description: 在当前对象表示的表面上使用指定的笔绘制指定的矩形。
type: docs
weight: 287
url: /zh/system.drawing/graphics/drawrectangle/
---
## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, int, int, int, int) 方法

在当前对象表示的表面上使用指定的笔绘制指定的矩形。

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, int x, int y, int width, int height)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 在绘制矩形时使用的笔 |
| x | int | 要绘制的矩形左上角的 X 坐标 |
| y | int | 要绘制的矩形左上角的 Y 坐标 |
| width | int | 要绘制的矩形的宽度 |
| height | int | 要绘制的矩形的高度 |

## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, float, float, float, float) 方法


在当前对象表示的表面上使用指定的笔绘制指定的矩形。

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, float x, float y, float width, float height)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 在绘制矩形时使用的笔 |
| x | **float** | 要绘制的矩形左上角的 X 坐标 |
| y | **float** | 要绘制的矩形左上角的 Y 坐标 |
| width | **float** | 要绘制的矩形的宽度 |
| height | **float** | 要绘制的矩形的高度 |

## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, Rectangle) 方法


在当前对象表示的表面上使用指定的笔绘制指定的矩形。

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, Rectangle rect)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 在绘制矩形时使用的笔 |
| rect | [Rectangle](../../rectangle/) | 一个 [Rectangle](../../rectangle/) 对象，指定要绘制的矩形的位置和大小 |

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Pen](../../pen/)
* 类 [Graphics](../)
* 类 [Rectangle](../../rectangle/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)