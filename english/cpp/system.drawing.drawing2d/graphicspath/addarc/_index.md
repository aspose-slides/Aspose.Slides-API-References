---
title: AddArc()
second_title: Aspose.Slides for C++ API Reference
description: Adds the specified elliptical arc to the path represented by the current object.
type: docs
weight: 183
url: /cpp/system.drawing.drawing2d/graphicspath/addarc/
---
## GraphicsPath::AddArc(float, float, float, float, float, float) method


Adds the specified elliptical arc to the path represented by the current object.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(float x, float y, float width, float height, float startAngle, float sweepAngle)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | The X coordinate of the upper left corner of the rectangle that bounds the ellipse from which the arc is drawn |
| y | **float** | The Y coordinate of the upper left corner of the rectangle that bounds the ellipse from which the arc is drawn |
| width | **float** | The width of the upper left corner of the rectangle that bounds the ellipse from which the arc is drawn |
| height | **float** | The height of the upper left corner of the rectangle that bounds the ellipse from which the arc is drawn |
| startAngle | **float** | Specifies the starting angle of the arc in degrees, measured clockwise from the X-axis |
| sweepAngle | **float** | Specifies the angle between the starting angle and the end of the arc |

## GraphicsPath::AddArc(int, int, int, int, float, float) method


Adds the specified elliptical arc to the path represented by the current object.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(int x, int y, int width, int height, float startAngle, float sweepAngle)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The X coordinate of the upper left corner of the rectangle that bounds the ellipse from which the arc is drawn |
| y | int | The Y coordinate of the upper left corner of the rectangle that bounds the ellipse from which the arc is drawn |
| width | int | The width of the upper left corner of the rectangle that bounds the ellipse from which the arc is drawn |
| height | int | The height of the upper left corner of the rectangle that bounds the ellipse from which the arc is drawn |
| startAngle | **float** | Specifies the starting angle of the arc in degrees, measured clockwise from the X-axis |
| sweepAngle | **float** | Specifies the angle between the starting angle and the end of the arc |

## GraphicsPath::AddArc(const RectangleF\&, float, float) method


Adds the specified elliptical arc to the path represented by the current object.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(const RectangleF &rect, float startAngle, float sweepAngle)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [RectangleF](../../../system.drawing/rectanglef/)\& | The rectangle that bounds the ellipse from which the arc is drawn |
| startAngle | **float** | Specifies the starting angle of the arc in degrees, measured clockwise from the X-axis |
| sweepAngle | **float** | Specifies the angle between the starting angle and the end of the arc |

## GraphicsPath::AddArc(const Rectangle\&, float, float) method


Adds the specified elliptical arc to the path represented by the current object.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(const Rectangle &rect, float startAngle, float sweepAngle)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../../system.drawing/rectangle/)\& | The rectangle that bounds the ellipse from which the arc is drawn |
| startAngle | **float** | Specifies the starting angle of the arc in degrees, measured clockwise from the X-axis |
| sweepAngle | **float** | Specifies the angle between the starting angle and the end of the arc |

## See Also

* Class [GraphicsPath](../)
* Class [RectangleF](../../../system.drawing/rectanglef/)
* Class [Rectangle](../../../system.drawing/rectangle/)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)