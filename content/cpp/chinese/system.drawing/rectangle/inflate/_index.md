---
title: Inflate()
second_title: Aspose.Slides for C++ API 参考
description: 增加当前对象所表示矩形的宽度和高度，同时保持矩形几何中心的位置。宽度和高度在两个方向上均按指定的量增加。
type: docs
weight: 261
url: /zh/system.drawing/rectangle/inflate/
---
## Rectangle::Inflate(int, int) 方法

增加当前对象所表示矩形的宽度和高度，同时保持矩形几何中心的位置。宽度和高度在两个方向上均按指定的量增加。

```cpp
void System::Drawing::Rectangle::Inflate(int width, int height)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| width | int | 在两个方向上增加矩形宽度的量 |
| height | int | 在两个方向上增加矩形高度的量 |

## Rectangle::Inflate(const Size\&) 方法

增加当前对象所表示矩形的宽度和高度，同时保持矩形几何中心的位置。宽度和高度分别按指定大小对象的 width 和 height 值在两个方向上增加。

```cpp
void System::Drawing::Rectangle::Inflate(const Size &size)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size | const [Size](../../size/)\& | [Size](../../size/) 对象，指定用于增大矩形宽度和高度的量 |

## Rectangle::Inflate(const Rectangle\&, int, int) 方法

增加指定对象所表示矩形的宽度和高度，同时保持矩形几何中心的位置。宽度和高度在两个方向上均按指定的量增加。

```cpp
static Rectangle System::Drawing::Rectangle::Inflate(const Rectangle &rect, int x, int y)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | 要膨胀的矩形 |
| x | int | 在两个方向上增加矩形宽度的量 |
| y | int | 在两个方向上增加矩形高度的量 |

### 返回值

[Rectangle](../) 对象，表示放大的矩形

## 另请参阅

* 类 [Rectangle](../)
* 类 [Size](../../size/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)