---
title: PointF
second_title: Aspose.Slides for C++ API Reference
description: "Represents a pair of single-precision floating point X and Y coordinates of a point on a 2-dimensional plane. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type."
type: docs
weight: 222
url: /cpp/system.drawing/pointf/
---
## PointF class


Represents a pair of single-precision floating point X and Y coordinates of a point on a 2-dimensional plane. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../../system/smartptr/) class to manage objects of this type.

```cpp
class PointF
```

## Methods

| Method | Description |
| --- | --- |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | Adds the width and height values of the specified [SizeF](../sizef/) object to the X and Y coordinates values of the specified [PointF](./) object correspondingly. |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [Size](../size/)\&) | Adds the width and height values of the specified [Size](../size/) object to the X and Y coordinates values of the specified [PointF](./) object correspondingly. |
| **bool** [Equals](./equals/)(const [PointF](./)\&) const | Determines if the current object and the specified object are equal, i.e. represent the same pair of X and Y coordinates values. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Determines if both X and Y coordinates values are equal to 0. |
| **float** [get_X](./get_x/)() const | Returns the value of X coordinate represented by the current object. |
| **float** [get_Y](./get_y/)() const | Returns the value of Y coordinate represented by the current object. |
| int [GetHashCode](./gethashcode/)() const | Returns a hash code for the current object. |
| **bool** [IsNull](./isnull/)() const | Always returns false. |
| explicit  [operator bool](./operator_bool/)() | Always returns true. |
|  [PointF](./pointf/)() | Constructs a new [PointF](./) object and initializes its X and Y coordinates values with 0. |
|  [PointF](./pointf/)(**float**, **float**) | Constructs a new [PointF](./) object and initializes it with the specified values. |
|  [PointF](./pointf/)(const [SizeF](../sizef/)\&) | Constructs a new [PointF](./) object and initializes its X and Y coordinates values with the values of width and height of the specifide [SizeF](../sizef/) object correspondingly. |
| void [set_X](./set_x/)(**float**) | Sets the value of X coordinate represented by the current object. |
| void [set_Y](./set_y/)(**float**) | Sets the value of Y coordinate represented by the current object. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | Subtracts the width and height values of the specified [SizeF](../sizef/) object from the X and Y coordinates values of the specified [PointF](./) object correspondingly. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [Size](../size/)\&) | Subtracts the width and height values of the specified [Size](../size/) object from the X and Y coordinates values of the specified [PointF](./) object correspondingly. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Returns the string representation of the pair of X and Y coordinates values represented by the current object. |
## Fields

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | An empty instance of [PointF](./) class whose X and Y coordinates values are 0. |
## See Also

* Namespace [System::Drawing](../)
* Library [Aspose.Slides](../../)
