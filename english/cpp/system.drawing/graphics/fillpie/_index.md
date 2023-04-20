---
title: FillPie()
second_title: Aspose.Slides for C++ API Reference
description: Fills the specified pie using the specified brush on the surface represented by the current object.
type: docs
weight: 274
url: /cpp/system.drawing/graphics/fillpie/
---
## Graphics::FillPie(const SharedPtr\<Brush\>\&, int, int, int, int, int, int) method


Fills the specified pie using the specified brush on the surface represented by the current object.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | A brush to use when filling the pie |
| x | int | The X coordinate of the upper left corner of the rectangle that defines the ellipse |
| y | int | The Y coordinate of the upper left corner of the rectangle that defines the ellipse |
| width | int | The width of the rectangle that defines the ellipse |
| height | int | The height of the rectangle that defines the ellipse |
| startAngle | int | Angle in degrees measured clockwise from the X axis to the starting point of the pie |
| sweepAngle | int | Angle in degrees measured clockwise from the **startAngle** to ending point of the pie |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, float, float, float, float, float, float) method


Fills the specified pie using the specified brush on the surface represented by the current object.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | A brush to use when filling the pie |
| x | **float** | The X coordinate of the upper left corner of the rectangle that defines the ellipse |
| y | **float** | The Y coordinate of the upper left corner of the rectangle that defines the ellipse |
| width | **float** | The width of the rectangle that defines the ellipse |
| height | **float** | The height of the rectangle that defines the ellipse |
| startAngle | **float** | Angle in degrees measured clockwise from the X axis to the starting point of the pie |
| sweepAngle | **float** | Angle in degrees measured clockwise from the **startAngle** to ending point of the pie |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, Rectangle, float, float) method


Fills the specified pie using the specified brush on the surface represented by the current object.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, Rectangle rect, float startAngle, float sweepAngle)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | A brush to use when filling the pie |
| rect | [Rectangle](../../rectangle/) | The rectangle that defines the ellipse |
| startAngle | **float** | Angle in degrees measured clockwise from the X axis to the starting point of the pie |
| sweepAngle | **float** | Angle in degrees measured clockwise from the **startAngle** to ending point of the pie |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Brush](../../brush/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)