---
title: Intersect()
second_title: Aspose.Slides for C++ API Reference
description: Replaces the rectangle represented by the current object with the rectangle that results from the its intersection with the rectangle represented by the specified object.
type: docs
weight: 274
url: /system.drawing/rectangle/intersect/
---
## Rectangle::Intersect(const Rectangle\&) method


Replaces the rectangle represented by the current object with the rectangle that results from the its intersection with the rectangle represented by the specified object.

```cpp
void System::Drawing::Rectangle::Intersect(const Rectangle &rect)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | The [Rectangle](../) object that represents the rectangle to intersect the rectangle represented by the current object with |

## Rectangle::Intersect(const Rectangle\&, const Rectangle\&) method


Returns a rectangle that is a result of intersection of the specified rectangles.

```cpp
static Rectangle System::Drawing::Rectangle::Intersect(const Rectangle &a, const Rectangle &b)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| a | const [Rectangle](../)\& | The first rectangle to intersect |
| b | const [Rectangle](../)\& | The second rectangle to intersect |

### Return Value

The result of intersection of **a** with **b**

## See Also

* Class [Rectangle](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)