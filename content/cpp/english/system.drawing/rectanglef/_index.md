---
title: RectangleF
second_title: Aspose.Slides for C++ API Reference
description: "Represents a rectangular area of an image defined as single-precision floating point X and Y coordinates of its upper left corner and its width and height. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type."
type: docs
weight: 248
url: /system.drawing/rectanglef/
---
## RectangleF class


Represents a rectangular area of an image defined as single-precision floating point X and Y coordinates of its upper left corner and its width and height. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../../system/smartptr/) class to manage objects of this type.

```cpp
class RectangleF
```

## Methods

| Method | Description |
| --- | --- |
| **bool** [Contains](./contains/)(**float**, **float**) | Determines if the specified point is located within the rectangle represented by the current object. |
| **bool** [Contains](./contains/)(const [PointF](../pointf/)\&) | Determines if the specified point is located within the rectangle represented by the current object. |
| **bool** [Contains](./contains/)(const [RectangleF](./)\&) | Determines if the specified rectangle is located within the rectangle represented by the current object. |
| **bool** [Equals](./equals/)(const [RectangleF](./)\&) const | Determines if the rectangles represented by the current and the specified objects are identical. |
| static [RectangleF](./) [FromLTRB](./fromltrb/)(**float**, **float**, **float**, **float**) | Constructs a new [RectangleF](./) object that represents a rectangle with the specified edge locations. |
| **float** [get_Bottom](./get_bottom/)() const | Returns the y coordinate of the bottom edge of the rectangle represented by the current object. |
| **float** [get_Height](./get_height/)() const | Returns the height of the rectangle represented by the current object. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Determines if X and Y coordinates of the upper left corner of the recangle represented by the current object as well as its width and height have values of 0. |
| **float** [get_Left](./get_left/)() const | Returns the X coordinate of the left edge of the rectangle represented by the current object. |
| [PointF](../pointf/) [get_Location](./get_location/)() const | Returns an instance of the [PointF](../pointf/) class that specifies the location of the upper left corner of the rectangle represented by the current object. |
| **float** [get_Right](./get_right/)() const | Returns the X coordinate of the right edge of the rectangle represented by the current object. |
| [SizeF](../sizef/) [get_Size](./get_size/)() const | Returns an instance of the [SizeF](../sizef/) class that specifies the width and height of the rectangle represented by the current object. |
| **float** [get_Top](./get_top/)() const | Returns the Y coordinate of the top edge of the rectangle represented by the current object. |
| **float** [get_Width](./get_width/)() const | Returns the width of the rectangle represented by the current object. |
| **float** [get_X](./get_x/)() const | Returns the X coordinate of the upper left corner of the rectangle represented by the current object. |
| **float** [get_Y](./get_y/)() const | Returns the Y coordinate of the upper left corner of the rectangle represented by the current object. |
| int [GetHashCode](./gethashcode/)() const | Returns a hash code of the current object. |
| void [Inflate](./inflate/)(**float**, **float**) | Increases the width and height of the rectangle represented by the current object, maintaining the location of the geometrical center of the rectangle. The width and height are increased in both directions by the specified amounts. |
| void [Inflate](./inflate/)(const [SizeF](../sizef/)\&) | Increases the width and height of the rectangle represented by the current object, maintaining the location of the geometrical center of the rectangle. The width and height are increased in both directions by the amounts specified by width and height values of the specified size object correspondingly. |
| static [RectangleF](./) [Inflate](./inflate/)(const [RectangleF](./)\&, **float**, **float**) | Increases the width and height of the rectangle represented by the specified object, maintaining the location of the geometrical center of the rectangle. The width and height are increased in both directions by the specified amounts. |
| void [Intersect](./intersect/)(const [RectangleF](./)\&) | Replaces the rectangle represented by the current object with the rectangle that results from the its intersection with the rectangle represented by the specified object. |
| static [RectangleF](./) [Intersect](./intersect/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | Returns a rectangle that is a result of intersection of the specified rectangles. |
| **bool** [IntersectsWith](./intersectswith/)(const [RectangleF](./)\&) | Determines if the rectangles represented by the current and specified objects intesect. |
| void [Offset](./offset/)(const [PointF](../pointf/)\&) | Offsets the position of the rectangle represented by the current object by the specified amounts. |
| void [Offset](./offset/)(**float**, **float**) | Offsets the position of the rectangle represented by the current object by the specified amounts. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Always returns true. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Always returns false. |
|  [RectangleF](./rectanglef/)() | Constructs a new instance of [RectangleF](./) object that represents a rectangle with X and Y coordinates and width and hegiht values set to 0. |
|  [RectangleF](./rectanglef/)(**float**, **float**, **float**, **float**) | Constructs a new instance of [RectangleF](./) object that represents a rectangle with the specified coordinates of its upper left corner and width and height. |
|  [RectangleF](./rectanglef/)(const [PointF](../pointf/)\&, const [SizeF](../sizef/)\&) | Constructs a new instance of [RectangleF](./) object that represents a rectangle with the coordinates of its upper left corner specified as an instance of [PointF](../pointf/) class and its width and height as an instance of [SizeF](../sizef/) class. |
| explicit  [RectangleF](./rectanglef/)(const [Rectangle](../rectangle/)\&) | Constructs a new instance of [RectangleF](./) object that represents the rectangle equivalent to the specified one. |
| void [set_Height](./set_height/)(**float**) | Sets the height of the rectangle represented by the current object. |
| void [set_Location](./set_location/)([PointF](../pointf/)) | Sets the location of the upper left corner of the rectangle represented by the current object. |
| void [set_Size](./set_size/)([SizeF](../sizef/)) | Sets the width and height of the rectangle represented by the current object. |
| void [set_Width](./set_width/)(**float**) | Sets the width of the rectangle represented by the current object. |
| void [set_X](./set_x/)(**float**) | Sets the X coordinate of the upper left corner of the rectangle represented by the current object. |
| void [set_Y](./set_y/)(**float**) | Sets the Y coordinate of the upper left corner of the rectangle represented by the current object. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Returns the string representation of the current object. |
| static [RectangleF](./) [Union](./union/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | Returns a rectangle that is a result of union of the specified rectangles. |
## Fields

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | An empty rectangle i.e. a rectangle whose location and size values have zero values. |
## See Also

* Namespace [System::Drawing](../)
* Library [Aspose.Slides](../../)