---
title: RectangleF class
second_title: Aspose.Slides for Python via .NET API Reference
description: Stores a set of four floating-point numbers that represent the location and size of a rectangle.
type: docs
url: /aspose.slides/rectanglef/
net_type: System.Drawing.RectangleF
---


## RectangleF class

Stores a set of four floating-point numbers that represent the location and size of a rectangle. Compatible with .NET `System.Drawing.RectangleF`.

**Inheritance:**[`RectangleF`](/slides/python-net/aspose.slides/rectanglef) → [`Rectangle`](/slides/python-net/aspose.slides/rectangle)

The RectangleF type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__(self, x=0.0, y=0.0, width=0.0, height=0.0)`](/slides/python-net/aspose.slides/rectanglef/__init__/#float-float-float-float) | Creates a rectangle with the specified location and size. |

## Properties

| Property | Description |
| :- | :- |
| [`x`](/slides/python-net/aspose.slides/rectanglef/x/) | Gets the x-coordinate of the upper-left corner of this rectangle.<br/>            Read-only **float**. |
| [`y`](/slides/python-net/aspose.slides/rectanglef/y/) | Gets the y-coordinate of the upper-left corner of this rectangle.<br/>            Read-only **float**. |
| [`width`](/slides/python-net/aspose.slides/rectanglef/width/) | Gets the width of this rectangle.<br/>            Read-only **float**. |
| [`height`](/slides/python-net/aspose.slides/rectanglef/height/) | Gets the height of this rectangle.<br/>            Read-only **float**. |
| [`left`](/slides/python-net/aspose.slides/rectanglef/left/) | Gets the x-coordinate of the left edge of this rectangle. Equals to `x`.<br/>            Read-only **float**. |
| [`top`](/slides/python-net/aspose.slides/rectanglef/top/) | Gets the y-coordinate of the top edge of this rectangle. Equals to `y`.<br/>            Read-only **float**. |
| [`right`](/slides/python-net/aspose.slides/rectanglef/right/) | Gets the x-coordinate that is the sum of `x` and `width` of this rectangle.<br/>            Read-only **float**. |
| [`bottom`](/slides/python-net/aspose.slides/rectanglef/bottom/) | Gets the y-coordinate that is the sum of `y` and `height` of this rectangle.<br/>            Read-only **float**. |
| [`is_empty`](/slides/python-net/aspose.slides/rectanglef/is_empty/) | Specifies whether all numeric properties of this rectangle have values of zero.<br/>            Read-only **bool**. |

## Methods

| Method | Description |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/aspose.slides/rectanglef/contains/#float-float) | Determines if the specified point is contained within this rectangle. |
| [`contains(self, point)`](/slides/python-net/aspose.slides/rectanglef/contains/#pointf) | Determines if the specified point is contained within this rectangle. |
| [`contains(self, rect)`](/slides/python-net/aspose.slides/rectanglef/contains/#rectanglef) | Determines if the rectangular region represented by `rect` is entirely contained within this rectangle. |


### Remarks

Rectangles are compared by their location and size with `==` and can be used as dictionary keys or set members.


### See Also
* class [`Rectangle`](/slides/python-net/aspose.slides/rectangle)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

