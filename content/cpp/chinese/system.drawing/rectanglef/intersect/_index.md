---
title: Intersect()
second_title: Aspose.Slides for C++ API 参考
description: 用当前对象表示的矩形替换为与指定对象表示的矩形相交后得到的矩形。
type: docs
weight: 274
url: /zh/system.drawing/rectanglef/intersect/
---
## RectangleF::Intersect(const RectangleF\&) 方法

用当前对象表示的矩形与指定对象表示的矩形相交的结果替换当前对象表示的矩形。

```cpp
void System::Drawing::RectangleF::Intersect(const RectangleF &rect)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | const [RectangleF](../)\& | 表示要与当前对象所表示的矩形相交的矩形的 [RectangleF](../) 对象 |

## RectangleF::Intersect(const RectangleF\&, const RectangleF\&) 方法

返回一个矩形，该矩形是指定矩形相交的结果。

```cpp
static RectangleF System::Drawing::RectangleF::Intersect(const RectangleF &a, const RectangleF &b)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | const [RectangleF](../)\& | 第一个要相交的矩形 |
| b | const [RectangleF](../)\& | 第二个要相交的矩形 |

### 返回值

**a** 与 **b** 相交的结果

## 另请参见

* 类 [RectangleF](../)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)