---
title: SizeF
second_title: "Aspose.Slides C++ API 参考"
description: "表示一对单精度浮点值，代表图像的宽度和高度。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 System::SmartPtr 类来管理此类型的对象。"
type: docs
weight: 287
url: /zh/system.drawing/sizef/
---
## SizeF 类


表示一对单精度浮点值，代表图像的宽度和高度。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 [System::SmartPtr](../../system/smartptr/) 类来管理此类型的对象。

```cpp
class SizeF
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static [SizeF](./) [Add](./add/)(const [SizeF](./)\&, const [SizeF](./)\&) | 返回一个新的 [SizeF](./) 对象，它是指定的 [SizeF](./) 对象的和，即其宽度值等于指定对象的宽度值之和，且高度值等于指定对象的高度值之和。 |
| **bool** [Equals](./equals/)(const [SizeF](./)\&) const | 确定当前对象与指定对象是否相等，即它们是否表示相同的宽度和高度值对。 |
| **float** [get_Height](./get_height/)() const | 返回当前对象表示的高度值。 |
| **bool** [get_IsEmpty](./get_isempty/)() const | 确定宽度和高度值是否均等于 0。 |
| **float** [get_Width](./get_width/)() const | 返回当前对象表示的宽度值。 |
| **int32_t** [GetHashCode](./gethashcode/)() const | 返回当前对象的哈希码。 |
|  [operator PointF](./operator_pointf/)() const | 将当前对象转换为 [Point](../point/) 对象实例，通过用当前对象的宽度和高度值分别初始化其 X 和 Y 坐标。 |
| [SizeF](./)\& [operator+=](./operator_plus_equal/)(const [SizeF](./)\&) | 将指定的 [SizeF](./) 对象的宽度和高度值分别加到当前 [SizeF](./) 对象的宽度和高度值上。 |
| void [set_Height](./set_height/)(**float**) | 设置当前对象表示的高度值。 |
| void [set_Width](./set_width/)(**float**) | 设置当前对象表示的宽度值。 |
|  [SizeF](./sizef/)() | 构造一个新的 [SizeF](./) 对象，并将其宽度和高度值初始化为 0。 |
|  [SizeF](./sizef/)(const [PointF](../pointf/)\&) | 构造一个新的 [SizeF](./) 对象，并将其宽度和高度值分别初始化为指定点的 X 和 Y 坐标值。 |
|  [SizeF](./sizef/)(**float**, **float**) | 构造一个新的 [SizeF](./) 对象，并用指定的值进行初始化。 |
| static [SizeF](./) [Subtract](./subtract/)(const [SizeF](./)\&, const [SizeF](./)\&) | 返回一个新的 [SizeF](./) 对象，它是 **size1** 减去 **size2** 的结果，即其宽度值为 **size1** 的宽度值减去 **size2** 的宽度值，且高度值为 **size1** 的高度值减去 **size2** 的高度值。 |
| [PointF](../pointf/) [ToPointF](./topointf/)() const | 将当前对象转换为 [Point](../point/) 对象实例，通过用当前对象的宽度和高度值分别初始化其 X 和 Y 坐标。 |
| [Size](../size/) [ToSize](./tosize/)() const | 从当前 [SizeF](./) 对象构造一个 [Size](../size/) 对象，方法是将 [SizeF](./) 对象的宽度和高度值截断为下一个更低的整数值。 |
| [System::String](../../system/string/) [ToString](./tostring/)() const | 返回当前对象所表示的宽度和高度值对的字符串表示。 |

## 字段

| 字段 | 描述 |
| --- | --- |
| static [Empty](./empty/) | 一个空的 [SizeF](./) 类实例，其宽度和高度值为 0。 |

## 另请参见

* 命名空间 [System::Drawing](../)
* 库 [Aspose.Slides](../../)