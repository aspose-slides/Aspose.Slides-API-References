---
title: Rectangle()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance of Rectangle object that represents a rectangle with X and Y coordinates and width and hegiht values set to 0.
type: docs
weight: 1
url: /cpp/system.drawing/rectangle/rectangle/
---
## Rectangle::Rectangle() constructor


Constructs a new instance of [Rectangle](../) object that represents a rectangle with X and Y coordinates and width and hegiht values set to 0.

```cpp
System::Drawing::Rectangle::Rectangle()
```

## Rectangle::Rectangle(int, int, int, int) constructor


Constructs a new instance of [Rectangle](../) object that represents a rectangle with the specified coordinates of its upper left corner and width and height.

```cpp
System::Drawing::Rectangle::Rectangle(int x, int y, int width, int height)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | int | A value of the X coordinate of the upper left corner of the rectangle |
| y | int | A value of the Y coordinate of the upper left corner of the rectangle |
| width | int | The width of the rectangle |
| height | int | The height of the rectangle |

## Rectangle::Rectangle(const Point\&, const Size\&) constructor


Constructs a new instance of [Rectangle](../) object that represents a rectangle with the coordinates of its upper left corner specified as an instance of [Point](../../point/) class and its width and height as an instance of [Size](../../size/) class.

```cpp
System::Drawing::Rectangle::Rectangle(const Point &location, const Size &size)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| location | const [Point](../../point/)\& | Specifies the location of the upper left corner of the rectangle |
| size | const [Size](../../size/)\& | Specifies the width and hegiht of the rectangle |

## Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_\&) constructor


Constructs a new instance of [Rectangle](../) object that represents the rectangle equivalent to the specified one.

```cpp
System::Drawing::Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_ &rect)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const **System::Windows::Forms::Screen::Rectangle_**\& | An instance of **System::Windows::Forms::Screen::Rectangle_** class that specifies the position and size of the rectangle to be represented by the object being constructed |

## See Also

* Class [Rectangle](../)
* Class [Point](../../point/)
* Class [Size](../../size/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)