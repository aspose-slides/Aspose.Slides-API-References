---
title: Inflate()
second_title: Aspose.Slides for C++ API Reference
description: Increases the width and height of the rectangle represented by the current object, maintaining the location of the geometrical center of the rectangle. The width and height are increased in both directions by the specified amounts.
type: docs
weight: 261
url: /system.drawing/rectanglef/inflate/
---
## RectangleF::Inflate(float, float) method


Increases the width and height of the rectangle represented by the current object, maintaining the location of the geometrical center of the rectangle. The width and height are increased in both directions by the specified amounts.

```cpp
void System::Drawing::RectangleF::Inflate(float width, float height)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| width | **float** | The amount by which the width of the rectangle is to be increased in both directions |
| height | **float** | The amount by which the height of the rectangle is to be increased in both directions |

## RectangleF::Inflate(const SizeF\&) method


Increases the width and height of the rectangle represented by the current object, maintaining the location of the geometrical center of the rectangle. The width and height are increased in both directions by the amounts specified by width and height values of the specified size object correspondingly.

```cpp
void System::Drawing::RectangleF::Inflate(const SizeF &size)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| size | const [SizeF](../../sizef/)\& | The [SizeF](../../sizef/) object specifying the amounts to increase the width and height of the rectangle by |

## RectangleF::Inflate(const RectangleF\&, float, float) method


Increases the width and height of the rectangle represented by the specified object, maintaining the location of the geometrical center of the rectangle. The width and height are increased in both directions by the specified amounts.

```cpp
static RectangleF System::Drawing::RectangleF::Inflate(const RectangleF &rect, float x, float y)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [RectangleF](../)\& | A rectangle to inflate |
| x | **float** | The amount by which the width of the rectangle is to be increased in both directions |
| y | **float** | The amount by which the height of the rectangle is to be increased in both directions |

### Return Value

The [RectangleF](../) object representing the enlarged rectangle

## See Also

* Class [RectangleF](../)
* Class [SizeF](../../sizef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)