---
title: RectangleF
second_title: Aspose.Slides for C++ API 参考
description: "表示图像的矩形区域，该区域由左上角的单精度浮点 X 和 Y 坐标以及宽度和高度定义。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 System::SmartPtr 类来管理此类型的对象。"
type: docs
weight: 248
url: /zh/system.drawing/rectanglef/
---
## RectangleF 类

表示图像的矩形区域，该区域由左上角的单精度浮点 X 和 Y 坐标以及宽度和高度定义。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 [System::SmartPtr](../../system/smartptr/) 类来管理此类型的对象。

```cpp
class RectangleF
```

## 方法

| 方法 | 描述 |
| --- | --- |
| **bool** [Contains](./contains/)(**float**, **float**) | 确定指定的点是否位于当前对象表示的矩形内部。 |
| **bool** [Contains](./contains/)(const [PointF](../pointf/)\&) | 确定指定的点是否位于当前对象表示的矩形内部。 |
| **bool** [Contains](./contains/)(const [RectangleF](./)\&) | 确定指定的矩形是否位于当前对象表示的矩形内部。 |
| **bool** [Equals](./equals/)(const [RectangleF](./)\&) const | 确定当前对象和指定对象表示的矩形是否相同。 |
| static [RectangleF](./) [FromLTRB](./fromltrb/)(**float**, **float**, **float**, **float**) | 构造一个新的 [RectangleF](./) 对象，该对象表示具有指定边缘位置的矩形。 |
| **float** [get_Bottom](./get_bottom/)() const | 返回当前对象表示的矩形底部边缘的 y 坐标。 |
| **float** [get_Height](./get_height/)() const | 返回当前对象表示的矩形的高度。 |
| **bool** [get_IsEmpty](./get_isempty/)() const | 确定当前对象表示的矩形的左上角 X、Y 坐标以及其宽度和高度是否全部为 0。 |
| **float** [get_Left](./get_left/)() const | 返回当前对象表示的矩形左边缘的 X 坐标。 |
| [PointF](../pointf/) [get_Location](./get_location/)() const | 返回一个 [PointF](../pointf/) 类的实例，该实例指定当前对象表示的矩形左上角的位置。 |
| **float** [get_Right](./get_right/)() const | 返回当前对象表示的矩形右边缘的 X 坐标。 |
| [SizeF](../sizef/) [get_Size](./get_size/)() const | 返回一个 [SizeF](../sizef/) 类的实例，该实例指定当前对象表示的矩形的宽度和高度。 |
| **float** [get_Top](./get_top/)() const | 返回当前对象表示的矩形顶部边缘的 Y 坐标。 |
| **float** [get_Width](./get_width/)() const | 返回当前对象表示的矩形的宽度。 |
| **float** [get_X](./get_x/)() const | 返回当前对象表示的矩形左上角的 X 坐标。 |
| **float** [get_Y](./get_y/)() const | 返回当前对象表示的矩形左上角的 Y 坐标。 |
| int [GetHashCode](./gethashcode/)() const | 返回当前对象的哈希码。 |
| void [Inflate](./inflate/)(**float**, **float**) | 在保持矩形几何中心位置不变的情况下，增加当前对象表示的矩形的宽度和高度。宽度和高度在两个方向上均按指定的量增加。 |
| void [Inflate](./inflate/)(const [SizeF](../sizef/)\&) | 在保持矩形几何中心位置不变的情况下，增加当前对象表示的矩形的宽度和高度。宽度和高度分别按指定大小对象的宽度和值对应的量在两个方向上增加。 |
| static [RectangleF](./) [Inflate](./inflate/)(const [RectangleF](./)\&, **float**, **float**) | 在保持矩形几何中心位置不变的情况下，增加指定对象表示的矩形的宽度和高度。宽度和高度在两个方向上均按指定的量增加。 |
| void [Intersect](./intersect/)(const [RectangleF](./)\&) | 用当前对象与指定对象的矩形相交后得到的矩形替换当前对象表示的矩形。 |
| static [RectangleF](./) [Intersect](./intersect/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | 返回由指定矩形相交得到的矩形。 |
| **bool** [IntersectsWith](./intersectswith/)(const [RectangleF](./)\&) | 确定当前对象和指定对象表示的矩形是否相交。 |
| void [Offset](./offset/)(const [PointF](../pointf/)\&) | 按指定的量偏移当前对象表示的矩形的位置。 |
| void [Offset](./offset/)(**float**, **float**) | 按指定的量偏移当前对象表示的矩形的位置。 |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | 始终返回 true。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 始终返回 false。 |
|  [RectangleF](./rectanglef/)() | 构造一个新的 [RectangleF](./) 对象实例，该对象表示一个 X、Y 坐标以及宽度和高度均设置为 0 的矩形。 |
|  [RectangleF](./rectanglef/)(**float**, **float**, **float**, **float**) | 构造一个新的 [RectangleF](./) 对象实例，该对象表示具有指定左上角坐标、宽度和高度的矩形。 |
|  [RectangleF](./rectanglef/)(const [PointF](../pointf/)\&, const [SizeF](../sizef/)\&) | 构造一个新的 [RectangleF](./) 对象实例，该对象的左上角坐标由 [PointF](../pointf/) 类的实例指定，宽度和高度由 [SizeF](../sizef/) 类的实例指定。 |
| explicit  [RectangleF](./rectanglef/)(const [Rectangle](../rectangle/)\&) | 构造一个新的 [RectangleF](./) 对象实例，该对象表示与指定矩形等价的矩形。 |
| void [set_Height](./set_height/)(**float**) | 设置当前对象表示的矩形的高度。 |
| void [set_Location](./set_location/)([PointF](../pointf/)) | 设置当前对象表示的矩形左上角的位置。 |
| void [set_Size](./set_size/)([SizeF](../sizef/)) | 设置当前对象表示的矩形的宽度和高度。 |
| void [set_Width](./set_width/)(**float**) | 设置当前对象表示的矩形的宽度。 |
| void [set_X](./set_x/)(**float**) | 设置当前对象表示的矩形左上角的 X 坐标。 |
| void [set_Y](./set_y/)(**float**) | 设置当前对象表示的矩形左上角的 Y 坐标。 |
| [System::String](../../system/string/) [ToString](./tostring/)() const | 返回当前对象的字符串表示。 |
| static [RectangleF](./) [Union](./union/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | 返回由指定矩形合并得到的矩形。 |

## 字段

| 字段 | 描述 |
| --- | --- |
| static [Empty](./empty/) | 一个空矩形，即位置和尺寸值均为零的矩形。 |

## 另见

* 命名空间 [System::Drawing](../)
* 库 [Aspose.Slides](../../)