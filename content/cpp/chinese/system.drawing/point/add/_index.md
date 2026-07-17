---
title: Add()
second_title: Aspose.Slides for C++ API 参考
description: 将指定 Size 对象的宽度和高度值分别添加到指定 Point 对象的 X 和 Y 坐标值中。
type: docs
weight: 183
url: /zh/system.drawing/point/add/
---
## Point::Add(const Point\&, const Size\&) 方法

将指定 [Size](../../size/) 对象的宽度和高度值分别添加到指定 [Point](../) 对象的 X 和 Y 坐标值。

```cpp
static Point System::Drawing::Point::Add(const Point &point, const Size &size)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| point | const [Point](../)\& | 要平移的点 |
| size | const [Size](../../size/)\& | [Size](../../size/) 对象，指定要添加到 **point** 坐标值的数值 |

### 返回值

一个新的 [Point](../) 对象，其 X 坐标值等于 **point** 的 X 坐标值与 **size** 的宽度值之和，Y 坐标值等于 **point** 的 Y 坐标值与 **size** 的高度值之和。

## 另见

* 类 [Point](../)
* 类 [Size](../../size/)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)