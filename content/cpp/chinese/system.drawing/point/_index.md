---
title: Point
second_title: Aspose.Slides for C++ API 参考
description: "表示二维平面上点的整数 X 和 Y 坐标对。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 System::SmartPtr 类来管理此类型的对象。"
type: docs
weight: 209
url: /zh/system.drawing/point/
---
## Point 类

表示二维平面上点的整数 X 和 Y 坐标对。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 [System::SmartPtr](../../system/smartptr/) 类来管理此类型的对象。

```cpp
class Point
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static [Point](./) [Add](./add/)(const [Point](./)\&, const [Size](../size/)\&) | 将指定的 [Size](../size/) 对象的宽度和高度值分别添加到指定的 [Point](./) 对象的 X 和 Y 坐标值中。 |
| static [Point](./) [Ceiling](./ceiling/)(const [PointF](../pointf/)\&) | 通过将 [PointF](../pointf/) 对象的 X 和 Y 坐标值向上取整到下一个更高的整数值，构造一个 [Point](./) 对象，来源于指定的 [PointF](../pointf/) 对象。 |
| **bool** [Equals](./equals/)(const [Point](./)\&) const | 判断当前对象与指定对象是否相等，即它们是否表示相同的 X 和 Y 坐标对。 |
| **bool** [get_IsEmpty](./get_isempty/)() const | 判断 X 和 Y 坐标值是否都等于 0。 |
| int [get_X](./get_x/)() const | 返回当前对象表示的 X 坐标的值。 |
| int [get_Y](./get_y/)() const | 返回当前对象表示的 Y 坐标的值。 |
| int [GetHashCode](./gethashcode/)() const | 返回当前对象的哈希码。 |
| size_t [getStdHash](./getstdhash/)() const | 返回当前对象的哈希值。 |
| **bool** [IsNull](./isnull/)() const | 永远返回 false。 |
| void [Offset](./offset/)(int, int) | 将当前对象表示的 X 和 Y 坐标值按指定的值进行偏移。 |
| void [Offset](./offset/)([Point](./)) | 将当前对象表示的 X 和 Y 坐标按指定的 [Point](./) 对象所表示的 X 和 Y 坐标值分别进行偏移。 |
|  [operator PointF](./operator_pointf/)() const | 构造一个 [PointF](../pointf/) 对象实例，并使用当前 [Point](./) 对象的 X 和 Y 坐标值进行初始化。 |
|  [operator Size](./operator_size/)() const | 构造一个 [Size](../size/) 对象实例，并使用当前对象表示的 X 和 Y 坐标值分别初始化其宽度和高度值。 |
|  [Point](./point/)() | 构造一个新的 [Point](./) 对象，并将其 X 和 Y 坐标值初始化为 0。 |
|  [Point](./point/)(int, int) | 构造一个新的 [Point](./) 对象，并使用指定的值进行初始化。 |
|  [Point](./point/)(const [Size](../size/)\&) | 构造一个新的 [Point](./) 对象，并使用指定的 [SizeF](../sizef/) 对象的宽度和高度值分别初始化其 X 和 Y 坐标值。 |
|  [Point](./point/)(int) | 构造一个新的 [Point](./) 对象，并使用指定 32 位整数的高 16 位形成的值初始化其 X 坐标，使用低 16 位形成的值初始化其 Y 坐标。 |
| static [Point](./) [Round](./round/)(const [PointF](../pointf/)\&) | 通过将 [PointF](../pointf/) 对象的 X 和 Y 坐标值四舍五入到最近的整数值，构造一个 [Point](./) 对象，来源于指定的 [PointF](../pointf/) 对象。 |
| void [set_X](./set_x/)(int) | 设置当前对象表示的 X 坐标值。 |
| void [set_Y](./set_y/)(int) | 设置当前对象表示的 Y 坐标值。 |
| static [Point](./) [Subtract](./subtract/)(const [Point](./)\&, const [Size](../size/)\&) | 将指定的 [Size](../size/) 对象的宽度和高度值分别从指定的 [Point](./) 对象的 X 和 Y 坐标值中减去。 |
| [String](../../system/string/) [ToString](./tostring/)() const | 返回当前对象表示的 X 和 Y 坐标对的字符串表示。 |
| static [Point](./) [Truncate](./truncate/)(const [PointF](../pointf/)\&) | 通过将 [PointF](../pointf/) 对象的 X 和 Y 坐标值截断到下一个更低的整数值，构造一个 [Point](./) 对象，来源于指定的 [PointF](../pointf/) 对象。 |

## 字段

| 字段 | 描述 |
| --- | --- |
| static [Empty](./empty/) | 一个空的 [Point](./) 类实例，其 X 和 Y 坐标值为 0。 |

## 另见

* 命名空间 [System::Drawing](../)
* 库 [Aspose.Slides](../../)