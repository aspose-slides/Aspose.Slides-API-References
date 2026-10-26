---
title: Inflate()
second_title: Aspose.Slides for C++ API 参考
description: 增加当前对象所表示的矩形的宽度和高度，同时保持矩形几何中心的位置。宽度和高度在两个方向上均按指定的数值增大。
type: docs
weight: 261
url: /zh/system.drawing/rectanglef/inflate/
---
## RectangleF::Inflate(float, float) 方法

增加当前对象所表示的矩形的宽度和高度，同时保持矩形几何中心的位置。宽度和高度在两个方向上均按指定的数值增大。

```cpp
void System::Drawing::RectangleF::Inflate(float width, float height)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| width | **float** | 在两个方向上宽度要增加的量 |
| height | **float** | 在两个方向上高度要增加的量 |

## RectangleF::Inflate(const SizeF\&) 方法

增加当前对象所表示的矩形的宽度和高度，同时保持矩形几何中心的位置。宽度和高度在两个方向上分别按指定大小对象的 width 和 height 值所对应的数值增大。

```cpp
void System::Drawing::RectangleF::Inflate(const SizeF &size)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size | const [SizeF](../../sizef/)\& | [SizeF](../../sizef/) 对象，指定用于增加矩形宽度和高度的量 |

## RectangleF::Inflate(const RectangleF\&, float, float) 方法

增加由指定对象所表示的矩形的宽度和高度，同时保持矩形几何中心的位置。宽度和高度在两个方向上均按指定的数值增大。

```cpp
static RectangleF System::Drawing::RectangleF::Inflate(const RectangleF &rect, float x, float y)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const [RectangleF](../)\& | 待膨胀的矩形 |
| x | **float** | 在两个方向上宽度要增加的量 |
| y | **float** | 在两个方向上高度要增加的量 |

### 返回值

[RectangleF](../) 对象，表示放大的矩形

## 另见

* 类 [RectangleF](../)
* 类 [SizeF](../../sizef/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)