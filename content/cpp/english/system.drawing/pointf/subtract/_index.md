---
title: Subtract()
second_title: Aspose.Slides for C++ API Reference
description: Subtracts the width and height values of the specified SizeF object from the X and Y coordinates values of the specified PointF object correspondingly.
type: docs
weight: 157
url: /system.drawing/pointf/subtract/
---
## PointF::Subtract(const PointF\&, const SizeF\&) method


Subtracts the width and height values of the specified [SizeF](../../sizef/) object from the X and Y coordinates values of the specified [PointF](../) object correspondingly.

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const SizeF &size)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| point | const [PointF](../)\& | The point to translate |
| size | const [SizeF](../../sizef/)\& | The [SizeF](../../sizef/) object that specifies the values to subtract from the coordinates values of the **point** |

### Return Value

A new [PointF](../) object whose X coordinate value is equal to the result of subtraction of the width value of **size** from the X coordinate value of **point** and Y coordinate value is equal to the result of subtraction of the height value of **size** from the Y coordinate value of **point**

## PointF::Subtract(const PointF\&, const Size\&) method


Subtracts the width and height values of the specified [Size](../../size/) object from the X and Y coordinates values of the specified [PointF](../) object correspondingly.

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const Size &size)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| point | const [PointF](../)\& | The point to translate |
| size | const [Size](../../size/)\& | The [Size](../../size/) object that specifies the values to subtract from the coordinates values of the **point** |

### Return Value

A new [PointF](../) object whose X coordinate value is equal to the result of subtraction of the width value of **size** from the X coordinate value of **point** and Y coordinate value is equal to the result of subtraction of the height value of **size** from the Y coordinate value of **point**

## See Also

* Class [PointF](../)
* Class [SizeF](../../sizef/)
* Class [Size](../../size/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)