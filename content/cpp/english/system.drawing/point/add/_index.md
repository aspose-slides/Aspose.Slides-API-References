---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Adds the width and height values of the specified Size object to the X and Y coordinates values of the specified Point object correspondingly.
type: docs
weight: 183
url: /system.drawing/point/add/
---
## Point::Add(const Point\&, const Size\&) method


Adds the width and height values of the specified [Size](../../size/) object to the X and Y coordinates values of the specified [Point](../) object correspondingly.

```cpp
static Point System::Drawing::Point::Add(const Point &point, const Size &size)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| point | const [Point](../)\& | The point to translate |
| size | const [Size](../../size/)\& | The [Size](../../size/) object that specifies the values to add to the coordinates values of the **point** |

### Return Value

A new [Point](../) object whose X coordinate value is equal to the sum of X coordinate value of **point** and the width value of **size** and Y coordinate value is equal to the sum of Y coordinate value of **point** and the height value of **size**

## See Also

* Class [Point](../)
* Class [Size](../../size/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)