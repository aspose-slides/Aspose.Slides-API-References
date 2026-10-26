---
title: RectangleF()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个新的 RectangleF 对象实例，该对象表示一个矩形，其 X 和 Y 坐标以及宽度和高度值均设为 0。
type: docs
weight: 1
url: /zh/system.drawing/rectanglef/rectanglef/
---
## RectangleF::RectangleF() 构造函数


构造一个新的 [RectangleF](../) 对象实例，该对象表示一个矩形，其 X 和 Y 坐标以及宽度和高度值均设为 0。

```cpp
System::Drawing::RectangleF::RectangleF()
```

## RectangleF::RectangleF(float, float, float, float) 构造函数


构造一个新的 [RectangleF](../) 对象实例，该对象表示一个矩形，其左上角的坐标和宽度、高度由指定值确定。

```cpp
System::Drawing::RectangleF::RectangleF(float x, float y, float width, float height)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | **float** | 矩形左上角的 X 坐标值 |
| y | **float** | 矩形左上角的 Y 坐标值 |
| width | **float** | 矩形的宽度 |
| height | **float** | 矩形的高度 |

## RectangleF::RectangleF(const PointF\&, const SizeF\&) 构造函数


构造一个新的 [RectangleF](../) 对象实例，该对象表示一个矩形，其左上角坐标由 [PointF](../../pointf/) 类的实例指定，宽度和高度由 [SizeF](../../sizef/) 类的实例指定。

```cpp
System::Drawing::RectangleF::RectangleF(const PointF &location, const SizeF &size)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| location | const [PointF](../../pointf/)\& | 指定矩形左上角的位置 |
| size | const [SizeF](../../sizef/)\& | 指定矩形的宽度和高度 |

## RectangleF::RectangleF(const Rectangle\&) 构造函数


构造一个新的 [RectangleF](../) 对象实例，该对象表示等同于指定矩形的矩形。

```cpp
System::Drawing::RectangleF::RectangleF(const Rectangle &rect)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 一个 [Rectangle](../../rectangle/) 类的实例，指定要由正在构造的对象表示的矩形的位置和大小 |

## 另请参见

* 类 [RectangleF](../)
* 类 [PointF](../../pointf/)
* 类 [SizeF](../../sizef/)
* 类 [Rectangle](../../rectangle/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)