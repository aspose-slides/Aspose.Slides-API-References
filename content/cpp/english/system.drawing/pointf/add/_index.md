---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Adds the width and height values of the specified SizeF object to the X and Y coordinates values of the specified PointF object correspondingly.
type: docs
weight: 144
url: /system.drawing/pointf/add/
---
## PointF::Add(const PointF\&, const SizeF\&) method


Adds the width and height values of the specified [SizeF](../../sizef/) object to the X and Y coordinates values of the specified [PointF](../) object correspondingly.

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const SizeF &size)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| point | const [PointF](../)\& | The point to translate |
| size | const [SizeF](../../sizef/)\& | The [SizeF](../../sizef/) object that specifies the values to add to the coordinates values of the **point** |

### Return Value

A new [PointF](../) object whose X coordinate value is equal to the sum of X coordinate value of **point** and the width value of **size** and Y coordinate value is equal to the sum of Y coordinate value of **point** and the height value of **size**

## PointF::Add(const PointF\&, const Size\&) method


Adds the width and height values of the specified [Size](../../size/) object to the X and Y coordinates values of the specified [PointF](../) object correspondingly.

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const Size &size)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| point | const [PointF](../)\& | The point to translate |
| size | const [Size](../../size/)\& | The [Size](../../size/) object that specifies the values to add to the coordinates values of the **point** |

### Return Value

A new [PointF](../) object whose X coordinate value is equal to the sum of X coordinate value of **point** and the width value of **size** and Y coordinate value is equal to the sum of Y coordinate value of **point** and the height value of **size**

## See Also

* Class [PointF](../)
* Class [SizeF](../../sizef/)
* Class [Size](../../size/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)