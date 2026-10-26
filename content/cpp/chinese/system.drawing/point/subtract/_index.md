---
title: Subtract()
second_title: Aspose.Slides for C++ API 参考
description: 从指定的 Point 对象的 X 和 Y 坐标值中相应地减去指定的 Size 对象的宽度和高度值。
type: docs
weight: 196
url: /zh/system.drawing/point/subtract/
---
## Point::Subtract(const Point\&, const Size\&) 方法

将指定的 [Size](../../size/) 对象的宽度和高度值从指定的 [Point](../) 对象的 X 和 Y 坐标值中相应地减去。

```cpp
static Point System::Drawing::Point::Subtract(const Point &point, const Size &size)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | const [Point](../)\& | 要平移的点 |
| size | const [Size](../../size/)\& | [Size](../../size/) 对象，用于指定从 **point** 坐标值中减去的数值 |

### 返回值

一个新的 [Point](../) 对象，其 X 坐标值等于 **size** 的宽度值从 **point** 的 X 坐标值减去的结果，Y 坐标值等于 **size** 的高度值从 **point** 的 Y 坐标值减去的结果。

## 另见

* 类 [Point](../)
* 类 [Size](../../size/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)