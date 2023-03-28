---
title: Subtract()
second_title: Aspose.Slides for C++ API Reference
description: Subtracts the width and height values of the specified Size object from the X and Y coordinates values of the specified Point object correspondingly.
type: docs
weight: 196
url: /cpp/system.drawing/point/subtract/
---
## Point::Subtract(const [Point](../)\&, const [Size](../../size/)\&) method


Subtracts the width and height values of the specified [Size](../../size/) object from the X and Y coordinates values of the specified [Point](../) object correspondingly.

```cpp
static Point System::Drawing::Point::Subtract(const Point &point, const Size &size)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| point | const [Point](../)\& | The point to translate |
| size | const [Size](../../size/)\& | The [Size](../../size/) object that specifies the values to subtract from the coordinates values of the **point** |

### Return Value

A new [Point](../) object whose X coordinate value is equal to the result of subtraction of the width value of **size** from the X coordinate value of **point** and Y coordinate value is equal to the result of subtraction of the height value of **size** from the Y coordinate value of **point**

## See Also

* Class [Point](../)
* Class [Size](../../size/)
* Class [Point](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
