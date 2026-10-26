---
title: Subtract()
second_title: Aspose.Slides C++ API 参考
description: 分别从指定的 PointF 对象的 X 和 Y 坐标值中减去指定的 SizeF 对象的宽度和高度值。
type: docs
weight: 157
url: /zh/system.drawing/pointf/subtract/
---
## PointF::Subtract(const PointF\&, const SizeF\&) 方法

从指定的 [PointF](../) 对象的 X 和 Y 坐标值中分别减去指定的 [SizeF](../../sizef/) 对象的宽度和高度值。

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const SizeF &size)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | const [PointF](../)\& | The point to translate |
| size | const [SizeF](../../sizef/)\& | The [SizeF](../../sizef/) object that specifies the values to subtract from the coordinates values of the **point** |

### 返回值

一个新的 [PointF](../) 对象，其 X 坐标值等于将 **size** 的宽度值从 **point** 的 X 坐标值减去的结果，Y 坐标值等于将 **size** 的高度值从 **point** 的 Y 坐标值减去的结果

## PointF::Subtract(const PointF\&, const Size\&) 方法

从指定的 [PointF](../) 对象的 X 和 Y 坐标值中分别减去指定的 [Size](../../size/) 对象的宽度和高度值。

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const Size &size)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | const [PointF](../)\& | The point to translate |
| size | const [Size](../../size/)\& | The [Size](../../size/) object that specifies the values to subtract from the coordinates values of the **point** |

### 返回值

一个新的 [PointF](../) 对象，其 X 坐标值等于将 **size** 的宽度值从 **point** 的 X 坐标值减去的结果，Y 坐标值等于将 **size** 的高度值从 **point** 的 Y 坐标值减去的结果

## 参见

* 类 [PointF](../)
* 类 [SizeF](../../sizef/)
* 类 [Size](../../size/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)