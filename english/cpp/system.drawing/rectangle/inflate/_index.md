---
title: Inflate()
second_title: Aspose.Slides for C++ API Reference
description: Increases the width and height of the rectangle represented by the current object, maintaining the location of the geometrical center of the rectangle. The width and height are increased in both directions by the specified amounts.
type: docs
weight: 261
url: /cpp/system.drawing/rectangle/inflate/
---
## Rectangle::Inflate(int, int) method


Increases the width and height of the rectangle represented by the current object, maintaining the location of the geometrical center of the rectangle. The width and height are increased in both directions by the specified amounts.

```cpp
void System::Drawing::Rectangle::Inflate(int width, int height)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The amount by which the width of the rectangle is to be increased in both directions |
| height | int | The amount by which the height of the rectangle is to be increased in both directions |

## Rectangle::Inflate(const Size\&) method


Increases the width and height of the rectangle represented by the current object, maintaining the location of the geometrical center of the rectangle. The width and height are increased in both directions by the amounts specified by width and height values of the specified size object correspondingly.

```cpp
void System::Drawing::Rectangle::Inflate(const Size &size)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| size | const [Size](../../size/)\& | The [Size](../../size/) object specifying the amounts to increase the width and height of the rectangle by |

## Rectangle::Inflate(const Rectangle\&, int, int) method


Increases the width and height of the rectangle represented by the specified object, maintaining the location of the geometrical center of the rectangle. The width and height are increased in both directions by the specified amounts.

```cpp
static Rectangle System::Drawing::Rectangle::Inflate(const Rectangle &rect, int x, int y)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | A rectangle to inflate |
| x | int | The amount by which the width of the rectangle is to be increased in both directions |
| y | int | The amount by which the height of the rectangle is to be increased in both directions |

### Return Value

The [Rectangle](../) object representing the enlarged rectangle

## See Also

* Class [Rectangle](../)
* Class [Size](../../size/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)