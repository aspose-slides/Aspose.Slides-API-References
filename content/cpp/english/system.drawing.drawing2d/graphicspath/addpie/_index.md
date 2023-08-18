---
title: AddPie()
second_title: Aspose.Slides for C++ API Reference
description: Adds the specified outline of the pie shape to the path represented by the current object.
type: docs
weight: 209
url: /system.drawing.drawing2d/graphicspath/addpie/
---
## GraphicsPath::AddPie(float, float, float, float, float, float) method


Adds the specified outline of the pie shape to the path represented by the current object.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(float x, float y, float width, float height, float startAngle, float sweepAngle)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | The X coordinate of the upper left corner of the rectangle that bounds the ellipse from which the pie is drawn |
| y | **float** | The Y coordinate of the upper left corner of the rectangle that bounds the ellipse from which the pie is drawn |
| width | **float** | The width of the upper left corner of the rectangle that bounds the ellipse from which the pie is drawn |
| height | **float** | The height of the upper left corner of the rectangle that bounds the ellipse from which the pie is drawn |
| startAngle | **float** | Specifies the starting angle of the pie in degrees, measured clockwise from the X-axis |
| sweepAngle | **float** | Specifies the angle between the starting angle and the end of the pie |

## GraphicsPath::AddPie(int, int, int, int, float, float) method


Adds the specified outline of the pie shape to the path represented by the current object.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(int x, int y, int width, int height, float startAngle, float sweepAngle)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The X coordinate of the upper left corner of the rectangle that bounds the ellipse from which the pie is drawn |
| y | int | The Y coordinate of the upper left corner of the rectangle that bounds the ellipse from which the pie is drawn |
| width | int | The width of the upper left corner of the rectangle that bounds the ellipse from which the pie is drawn |
| height | int | The height of the upper left corner of the rectangle that bounds the ellipse from which the pie is drawn |
| startAngle | **float** | Specifies the starting angle of the pie in degrees, measured clockwise from the X-axis |
| sweepAngle | **float** | Specifies the angle between the starting angle and the end of the pie |

## GraphicsPath::AddPie(const Rectangle\&, float, float) method


Adds the specified outline of the pie shape to the path represented by the current object.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(const Rectangle &rect, float startAngle, float sweepAngle)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../../system.drawing/rectangle/)\& | The rectangle that bounds the ellipse from which the pie is drawn |
| startAngle | **float** | Specifies the starting angle of the pie in degrees, measured clockwise from the X-axis |
| sweepAngle | **float** | Specifies the angle between the starting angle and the end of the pie |

## See Also

* Class [GraphicsPath](../)
* Class [Rectangle](../../../system.drawing/rectangle/)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)