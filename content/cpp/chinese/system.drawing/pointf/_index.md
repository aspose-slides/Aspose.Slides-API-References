---
title: PointF
second_title: Aspose.Slides C++ API 参考
description: "表示二维平面上点的单精度浮点数 X 和 Y 坐标对。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 System::SmartPtr 类来管理此类型的对象。"
type: docs
weight: 222
url: /zh/system.drawing/pointf/
---
## PointF 类


表示二维平面上点的单精度浮点数 X 和 Y 坐标对。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 [System::SmartPtr](../../system/smartptr/) 类来管理此类型的对象。

```cpp
class PointF
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | 将指定的 [SizeF](../sizef/) 对象的宽度和高度值分别添加到指定的 [PointF](./) 对象的 X 和 Y 坐标值中。 |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [Size](../size/)\&) | 将指定的 [Size](../size/) 对象的宽度和高度值分别添加到指定的 [PointF](./) 对象的 X 和 Y 坐标值中。 |
| **bool** [Equals](./equals/)(const [PointF](./)\&) const | 确定当前对象和指定对象是否相等，即它们是否表示相同的 X 和 Y 坐标对。 |
| **bool** [get_IsEmpty](./get_isempty/)() const | 确定 X 和 Y 坐标值是否均为 0。 |
| **float** [get_X](./get_x/)() const | 返回当前对象表示的 X 坐标的值。 |
| **float** [get_Y](./get_y/)() const | 返回当前对象表示的 Y 坐标的值。 |
| int [GetHashCode](./gethashcode/)() const | 为当前对象返回哈希码。 |
| **bool** [IsNull](./isnull/)() const | 总是返回 false。 |
| explicit  [operator bool](./operator_bool/)() | 总是返回 true。 |
|  [PointF](./pointf/)() | 构造一个新的 [PointF](./) 对象，并将其 X 和 Y 坐标值初始化为 0。 |
|  [PointF](./pointf/)(**float**, **float**) | 构造一个新的 [PointF](./) 对象，并使用指定的值进行初始化。 |
|  [PointF](./pointf/)(const [SizeF](../sizef/)\&) | 构造一个新的 [PointF](./) 对象，并将其 X 和 Y 坐标值分别初始化为指定的 [SizeF](../sizef/) 对象的宽度和高度值。 |
| void [set_X](./set_x/)(**float**) | 设置当前对象表示的 X 坐标的值。 |
| void [set_Y](./set_y/)(**float**) | 设置当前对象表示的 Y 坐标的值。 |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | 将指定的 [SizeF](../sizef/) 对象的宽度和高度值分别从指定的 [PointF](./) 对象的 X 和 Y 坐标值中减去。 |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [Size](../size/)\&) | 将指定的 [Size](../size/) 对象的宽度和高度值分别从指定的 [PointF](./) 对象的 X 和 Y 坐标值中减去。 |
| [System::String](../../system/string/) [ToString](./tostring/)() const | 返回当前对象表示的 X 和 Y 坐标对的字符串表示。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| static [Empty](./empty/) | 一个空实例 [PointF](./) 类，其 X 和 Y 坐标值为 0。 |
## 另请参阅

* 命名空间 [System::Drawing](../)
* 库 [Aspose.Slides](../../)