---
title: Intersect()
second_title: Aspose.Slides for C++ API 参考
description: 将当前对象表示的矩形替换为与指定对象表示的矩形相交后得到的矩形。
type: docs
weight: 274
url: /zh/system.drawing/rectangle/intersect/
---
## Rectangle::Intersect(const Rectangle\&) 方法

将当前对象表示的矩形替换为与指定对象表示的矩形相交后得到的矩形。

```cpp
void System::Drawing::Rectangle::Intersect(const Rectangle &rect)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | [Rectangle](../) 对象，表示要与当前对象表示的矩形相交的矩形 |

## Rectangle::Intersect(const Rectangle\&, const Rectangle\&) 方法

返回一个矩形，该矩形是指定矩形相交的结果。

```cpp
static Rectangle System::Drawing::Rectangle::Intersect(const Rectangle &a, const Rectangle &b)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | const [Rectangle](../)\& | 要相交的第一个矩形 |
| b | const [Rectangle](../)\& | 要相交的第二个矩形 |

### 返回值

**a** 与 **b** 相交的结果

## 参见

* 类 [Rectangle](../)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)