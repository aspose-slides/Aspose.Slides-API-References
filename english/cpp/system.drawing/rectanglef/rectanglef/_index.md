---
title: RectangleF()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance of RectangleF object that represents a rectangle with X and Y coordinates and width and hegiht values set to 0.
type: docs
weight: 1
url: /cpp/system.drawing/rectanglef/rectanglef/
---
## RectangleF::RectangleF() constructor


Constructs a new instance of [RectangleF](../) object that represents a rectangle with X and Y coordinates and width and hegiht values set to 0.

```cpp
System::Drawing::RectangleF::RectangleF()
```

## RectangleF::RectangleF(float, float, float, float) constructor


Constructs a new instance of [RectangleF](../) object that represents a rectangle with the specified coordinates of its upper left corner and width and height.

```cpp
System::Drawing::RectangleF::RectangleF(float x, float y, float width, float height)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | A value of the X coordinate of the upper left corner of the rectangle |
| y | **float** | A value of the Y coordinate of the upper left corner of the rectangle |
| width | **float** | The width of the rectangle |
| height | **float** | The height of the rectangle |

## RectangleF::RectangleF(const PointF\&, const SizeF\&) constructor


Constructs a new instance of [RectangleF](../) object that represents a rectangle with the coordinates of its upper left corner specified as an instance of [PointF](../../pointf/) class and its width and height as an instance of [SizeF](../../sizef/) class.

```cpp
System::Drawing::RectangleF::RectangleF(const PointF &location, const SizeF &size)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| location | const [PointF](../../pointf/)\& | Specifies the location of the upper left corner of the rectangle |
| size | const [SizeF](../../sizef/)\& | Specifies the width and hegiht of the rectangle |

## RectangleF::RectangleF(const Rectangle\&) constructor


Constructs a new instance of [RectangleF](../) object that represents the rectangle equivalent to the specified one.

```cpp
System::Drawing::RectangleF::RectangleF(const Rectangle &rect)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | An instance of [Rectangle](../../rectangle/) class that specifies the position and size of the rectangle to be represented by the object being constructed |

## See Also

* Class [RectangleF](../)
* Class [PointF](../../pointf/)
* Class [SizeF](../../sizef/)
* Class [Rectangle](../../rectangle/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)