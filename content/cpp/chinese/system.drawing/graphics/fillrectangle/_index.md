---
title: FillRectangle()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的画刷填充指定的矩形。
type: docs
weight: 326
url: /zh/system.drawing/graphics/fillrectangle/
---
## Graphics::FillRectangle(const SharedPtr\<Brush\>\&, float, float, float, float) 方法

用指定的画刷填充指定的矩形。

```cpp
void System::Drawing::Graphics::FillRectangle(const SharedPtr<Brush> &brush, float x, float y, float width, float height)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 用于填充的 [Brush](../../brush/) 对象 |
| x | **float** | 要填充的矩形左上角的 X 坐标 |
| y | **float** | 要填充的矩形左上角的 Y 坐标 |
| width | **float** | 要填充的矩形的宽度 |
| height | **float** | 要填充的矩形的高度 |

## Graphics::FillRectangle(const SharedPtr\<Brush\>\&, int, int, int, int) 方法

用指定的画刷填充指定的矩形。

```cpp
void System::Drawing::Graphics::FillRectangle(const SharedPtr<Brush> &brush, int x, int y, int width, int height)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 用于填充的 [Brush](../../brush/) 对象 |
| x | int | 要填充的矩形左上角的 X 坐标 |
| y | int | 要填充的矩形左上角的 Y 坐标 |
| width | int | 要填充的矩形的宽度 |
| height | int | 要填充的矩形的高度 |

## Graphics::FillRectangle(const SharedPtr\<Brush\>\&, Rectangle) 方法

用指定的画刷填充指定的矩形。

```cpp
void System::Drawing::Graphics::FillRectangle(const SharedPtr<Brush> &brush, Rectangle rect)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 用于填充的 [Brush](../../brush/) 对象 |
| rect | [Rectangle](../../rectangle/) | 指定要填充的矩形位置和大小的 [Rectangle](../../rectangle/) 对象 |

## Graphics::FillRectangle(const SharedPtr\<Brush\>\&, RectangleF) 方法

用指定的画刷填充指定的矩形。

```cpp
void System::Drawing::Graphics::FillRectangle(const SharedPtr<Brush> &brush, RectangleF rect)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 用于填充的 [Brush](../../brush/) 对象 |
| rect | [RectangleF](../../rectanglef/) | 指定要填充的矩形位置和大小的 [RectangleF](../../rectanglef/) 对象 |

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Brush](../../brush/)
* 类 [Graphics](../)
* 类 [Rectangle](../../rectangle/)
* 类 [RectangleF](../../rectanglef/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)