---
title: Add()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的 SizeF 对象的宽度和高度值分别添加到指定的 PointF 对象的 X 和 Y 坐标值中。
type: docs
weight: 144
url: /zh/system.drawing/pointf/add/
---
## PointF::Add(const PointF\&, const SizeF\&) 方法


将指定的 [SizeF](../../sizef/) 对象的宽度和高度值分别添加到指定的 [PointF](../) 对象的 X 和 Y 坐标值中。

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const SizeF &size)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | const [PointF](../)\& | 用于平移的 point |
| size | const [SizeF](../../sizef/)\& | 指定要添加到 **point** 坐标值的值的 [SizeF](../../sizef/) 对象 |

### 返回值

返回一个新的 [PointF](../) 对象，其 X 坐标值等于 **point** 的 X 坐标值与 **size** 的宽度值之和，Y 坐标值等于 **point** 的 Y 坐标值与 **size** 的高度值之和

## PointF::Add(const PointF\&, const Size\&) 方法


将指定的 [Size](../../size/) 对象的宽度和高度值分别添加到指定的 [PointF](../) 对象的 X 和 Y 坐标值中。

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const Size &size)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | const [PointF](../)\& | 用于平移的 point |
| size | const [Size](../../size/)\& | 指定要添加到 **point** 坐标值的值的 [Size](../../size/) 对象 |

### 返回值

返回一个新的 [PointF](../) 对象，其 X 坐标值等于 **point** 的 X 坐标值与 **size** 的宽度值之和，Y 坐标值等于 **point** 的 Y 坐标值与 **size** 的高度值之和

## 另请参阅

* 类 [PointF](../)
* 类 [SizeF](../../sizef/)
* 类 [Size](../../size/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)