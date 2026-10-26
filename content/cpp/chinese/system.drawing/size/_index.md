---
title: Size
second_title: Aspose.Slides for C++ API 参考
description: "表示一对整数值，用于表示图像的宽度和高度。此类型应在栈上分配并通过值或引用传递给函数。切勿使用 System::SmartPtr 类来管理此类型的对象。"
type: docs
weight: 274
url: /zh/system.drawing/size/
---
## 大小类

表示一对整数值，用于表示图像的宽度和高度。此类型应在栈上分配并通过值或引用传递给函数。切勿使用 [System::SmartPtr](../../system/smartptr/) 类来管理此类型的对象。

```cpp
class Size
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static [Size](./) [Add](./add/)(const [Size](./)\&, const [Size](./)\&) | 返回一个新的 [Size](./) 对象，该对象是指定 [Size](./) 对象的和，即其宽度值等于指定对象的宽度值之和，且高度值等于指定对象的高度值之和。 |
| static [Size](./) [Ceiling](./ceiling/)(const [SizeF](../sizef/)\&) | 从指定的 [SizeF](../sizef/) 对象构造一个 [Size](./) 对象，方法是将 [SizeF](../sizef/) 对象的宽度和高度值向上取整到下一个更大的整数。 |
| **bool** [Equals](./equals/)(const [Size](./)\&) const | 确定当前对象和指定对象是否相等，即它们是否表示相同的宽度和高度值的对。 |
| int [get_Height](./get_height/)() const | 返回当前对象表示的高度值。 |
| **bool** [get_IsEmpty](./get_isempty/)() const | 确定宽度和高度值是否都等于 0。 |
| int [get_Width](./get_width/)() const | 返回当前对象表示的宽度值。 |
| **int32_t** [GetHashCode](./gethashcode/)() const | 返回当前对象的哈希码。 |
| [operator Point](./operator_point/)() const | 构造一个 [Point](../point/) 对象实例，并相应地以当前对象的宽度和高度值初始化其 X 与 Y 坐标。 |
| [operator SizeF](./operator_sizef/)() const | 构造一个 [SizeF](../sizef/) 对象的实例，并使用当前 [Size](./) 对象的宽度和高度值进行初始化。 |
| static [Size](./) [Round](./round/)(const [SizeF](../sizef/)\&) | 从指定的 [SizeF](../sizef/) 对象构造一个 [Size](./) 对象，方法是将 [SizeF](../sizef/) 对象的宽度和高度值四舍五入到最近的整数。 |
| void [set_Height](./set_height/)(int) | 设置当前对象表示的高度值。 |
| void [set_Width](./set_width/)(int) | 设置当前对象表示的宽度值。 |
| [Size](./size/)() | 构造一个新的 [Size](./) 对象，并将其宽度和高度值初始化为 0。 |
| [Size](./size/)(const [Point](../point/)\&) | 构造一个新的 [Size](./) 对象，并分别以指定点的 X 和 Y 坐标值初始化其宽度和高度值。 |
| [Size](./size/)(int, int) | 构造一个新的 [Size](./) 对象，并使用指定的值进行初始化。 |
| static [Size](./) [Subtract](./subtract/)(const [Size](./)\&, const [Size](./)\&) | 返回一个新的 [Size](./) 对象，该对象是 **size1** 减去 **size2** 的结果，即其宽度值为 **size1** 的宽度值减去 **size2** 的宽度值，且高度值为 **size1** 的高度值减去 **size2** 的高度值。 |
| [String](../../system/string/) [ToString](./tostring/)() const | 返回当前对象所表示的宽度和高度值对的字符串表示。 |
| static [Size](./) [Truncate](./truncate/)(const [SizeF](../sizef/)\&) | 从指定的 [SizeF](../sizef/) 对象构造一个 [Size](./) 对象，方法是将 [SizeF](../sizef/) 对象的宽度和高度值截断到下一个更低的整数。 |

## 字段

| 字段 | 描述 |
| --- | --- |
| static [Empty](./empty/) | 一个空的 [Size](./) 类实例，其宽度和高度值均为 0。 |

## 另请参阅

* 命名空间 [System::Drawing](../)
* 库 [Aspose.Slides](../../)