---
title: Rectangle
second_title: "Aspose.Slides for C++ API 参考"
description: "表示图像的矩形区域，由左上角的整数 X 和 Y 坐标以及宽度和高度定义。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 System::SmartPtr 类来管理此类型的对象。"
type: docs
weight: 235
url: /zh/system.drawing/rectangle/
---
## Rectangle 类


表示图像的矩形区域，由左上角的整数 X 和 Y 坐标以及宽度和高度定义。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 [System::SmartPtr](../../system/smartptr/) 类来管理此类型的对象。

```cpp
class Rectangle
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static [Rectangle](./) [Ceiling](./ceiling/)(const [RectangleF](../rectanglef/)\&) | 通过将 [RectangleF](../rectanglef/) 对象的位置和大小值向上取整到下一个更大的整数，从指定的 [RectangleF](../rectanglef/) 对象构造一个 [Rectangle](./) 对象。 |
| **bool** [Contains](./contains/)(int, int) const | 确定指定的点是否位于当前对象所表示的矩形内部。 |
| **bool** [Contains](./contains/)(const [Point](../point/)\&) const | 确定指定的点是否位于当前对象所表示的矩形内部。 |
| **bool** [Contains](./contains/)(const [Rectangle](./)\&) const | 确定指定的矩形是否位于当前对象所表示的矩形内部。 |
| **bool** [Equals](./equals/)(const [Rectangle](./)\&) const | 确定当前对象和指定对象所表示的矩形是否相同。 |
| static [Rectangle](./) [FromLTRB](./fromltrb/)(int, int, int, int) | 构造一个新的 [Rectangle](./) 对象，该对象表示具有指定边缘位置的矩形。 |
| int [get_Bottom](./get_bottom/)() const | 返回当前对象所表示的矩形底边的 y 坐标。 |
| int [get_Height](./get_height/)() const | 返回当前对象所表示的矩形的高度。 |
| **bool** [get_IsEmpty](./get_isempty/)() const | 确定当前对象所表示的矩形的左上角 X、Y 坐标以及其宽度和高度是否全部为 0。 |
| int [get_Left](./get_left/)() const | 返回当前对象所表示的矩形左边缘的 X 坐标。 |
| [Point](../point/) [get_Location](./get_location/)() const | 返回一个 [Point](../point/) 类的实例，指定当前对象所表示的矩形左上角的位置。 |
| int [get_Right](./get_right/)() const | 返回当前对象所表示的矩形右边缘的 X 坐标。 |
| [Size](../size/) [get_Size](./get_size/)() const | 返回一个 [Size](../size/) 类的实例，指定当前对象所表示的矩形的宽度和高度。 |
| int [get_Top](./get_top/)() const | 返回当前对象所表示的矩形上边缘的 Y 坐标。 |
| int [get_Width](./get_width/)() const | 返回当前对象所表示的矩形的宽度。 |
| int [get_X](./get_x/)() const | 返回当前对象所表示的矩形左上角的 X 坐标。 |
| int [get_Y](./get_y/)() const | 返回当前对象所表示的矩形左上角的 Y 坐标。 |
| int [GetHashCode](./gethashcode/)() const | 返回当前对象的哈希码。 |
| void [Inflate](./inflate/)(int, int) | 在保持矩形几何中心位置不变的情况下，增加当前对象所表示的矩形的宽度和高度。宽度和高度在两个方向上均按指定的量增加。 |
| void [Inflate](./inflate/)(const [Size](../size/)\&) | 在保持矩形几何中心位置不变的情况下，增加当前对象所表示的矩形的宽度和高度。宽度和高度分别按指定尺寸对象的宽度和高度值所对应的量在两个方向上增加。 |
| static [Rectangle](./) [Inflate](./inflate/)(const [Rectangle](./)\&, int, int) | 在保持矩形几何中心位置不变的情况下，增加指定对象所表示的矩形的宽度和高度。宽度和高度在两个方向上均按指定的量增加。 |
| void [Intersect](./intersect/)(const [Rectangle](./)\&) | 用当前对象与指定对象的矩形相交得到的矩形替换当前对象所表示的矩形。 |
| static [Rectangle](./) [Intersect](./intersect/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | 返回指定矩形相交的结果矩形。 |
| **bool** [IntersectsWith](./intersectswith/)(const [Rectangle](./)\&) | 确定当前对象和指定对象所表示的矩形是否相交。 |
| void [Offset](./offset/)(const [Point](../point/)\&) | 按指定的量偏移当前对象所表示的矩形的位置。 |
| void [Offset](./offset/)(int, int) | 按指定的量偏移当前对象所表示的矩形的位置。 |
| [operator RectangleF](./operator_rectanglef/)() const | 返回一个 [RectangleF](../rectanglef/) 对象，表示与当前对象所表示的矩形等价的矩形。 |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | 始终返回 true。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 始终返回 false。 |
| [Rectangle](./rectangle/)() | 构造一个新的 [Rectangle](./) 对象实例，该对象表示一个 X、Y 坐标以及宽度和高度均为 0 的矩形。 |
| [Rectangle](./rectangle/)(int, int, int, int) | 构造一个新的 [Rectangle](./) 对象实例，该对象表示一个具有指定左上角坐标、宽度和高度的矩形。 |
| [Rectangle](./rectangle/)(const [Point](../point/)\&, const [Size](../size/)\&) | 构造一个新的 [Rectangle](./) 对象实例，该对象表示一个矩形，其左上角坐标由 [Point](../point/) 类的实例指定，宽度和高度由 [Size](../size/) 类的实例指定。 |
| [Rectangle](./rectangle/)(const **System::Windows::Forms::Screen::Rectangle_**\&) | 构造一个新的 [Rectangle](./) 对象实例，表示与指定矩形等价的矩形。 |
| static [Rectangle](./) [Round](./round/)(const [RectangleF](../rectanglef/)\&) | 从指定的 [RectangleF](../rectanglef/) 对象构造一个 [Rectangle](./) 对象，通过将 [RectangleF](../rectanglef/) 对象的位置和大小值四舍为最近的整数。 |
| void [set_Height](./set_height/)(int) | 设置当前对象所表示的矩形的高度。 |
| void [set_Location](./set_location/)([Point](../point/)) | 设置当前对象所表示的矩形左上角的位置。 |
| void [set_Size](./set_size/)([Size](../size/)) | 设置当前对象所表示的矩形的宽度和高度。 |
| void [set_Width](./set_width/)(int) | 设置当前对象所表示的矩形的宽度。 |
| void [set_X](./set_x/)(int) | 设置当前对象所表示的矩形左上角的 X 坐标。 |
| void [set_Y](./set_y/)(int) | 设置当前对象所表示的矩形左上角的 Y 坐标。 |
| [String](../../system/string/) [ToString](./tostring/)() const | 返回当前对象的字符串表示。 |
| static [Rectangle](./) [Truncate](./truncate/)(const [RectangleF](../rectanglef/)\&) | 从指定的 [RectangleF](../rectanglef/) 对象构造一个 [Rectangle](./) 对象，通过将 [RectangleF](../rectanglef/) 对象的位置和大小值向下取整到下一个更低的整数。 |
| static [Rectangle](./) [Union](./union/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | 返回指定矩形的并集结果矩形。 |

## 字段

| 字段 | 描述 |
| --- | --- |
| static [Empty](./empty/) | 一个空矩形，即位置和大小值均为零的矩形。 |

## 参见

* 命名空间 [System::Drawing](../)
* 库 [Aspose.Slides](../../)