---
title: Point()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new Point object and initializes its X and Y coordinates values with 0.
type: docs
weight: 1
url: /cpp/system.drawing/point/point/
---
## Point::Point() constructor


Constructs a new [Point](../) object and initializes its X and Y coordinates values with 0.

```cpp
System::Drawing::Point::Point()
```

## Point::Point(int, int) constructor


Constructs a new [Point](../) object and initializes it with the specified values.

```cpp
System::Drawing::Point::Point(int x, int y)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The value of X coordinate |
| y | int | The value of Y coordinate |

## Point::Point(const Size\&) constructor


Constructs a new [Point](../) object and initializes its X and Y coordinates values with the values of width and height of the specifide [SizeF](../../sizef/) object correspondingly.

```cpp
System::Drawing::Point::Point(const Size &size)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| size | const [Size](../../size/)\& | A [SizeF](../../sizef/) object whose width and height values are used to initialize X and Y coordinates values of the [Point](../) object being created |

## Point::Point(int) constructor


Constructs a new [Point](../) object and initializes its X coordinate value with a value formed by high 16 bits of the specified 32-bit integer and its Y coordinate value with a vale formed by low 16 bits of the specified 32-bit integer value value.

```cpp
System::Drawing::Point::Point(int dw)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| dw | int | The 32-bit integer value whose high 16 bits specify the X coordinate value and low 16 bits specify the Y coordinate value of the object being created |

## See Also

* Class [Point](../)
* Class [Size](../../size/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)