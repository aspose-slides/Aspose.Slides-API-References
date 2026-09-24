---
title: Rectangle class
second_title: Aspose.Slides for Python via .NET API Reference
description: Stores a set of four integers that represent the location and size of a rectangle.
type: docs
url: /aspose.slides/rectangle/
net_type: System.Drawing.Rectangle
---


## Rectangle class

Stores a set of four integers that represent the location and size of a rectangle. Compatible with .NET `System.Drawing.Rectangle`.

The Rectangle type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__(self, x=0, y=0, width=0, height=0)`](/slides/python-net/aspose.slides/rectangle/__init__/#int-int-int-int) | Creates a rectangle with the specified location and size. Float values are truncated to integers. |

## Properties

| Property | Description |
| :- | :- |
| [`x`](/slides/python-net/aspose.slides/rectangle/x/) | Gets the x-coordinate of the upper-left corner of this rectangle.<br/>            Read-only **int**. |
| [`y`](/slides/python-net/aspose.slides/rectangle/y/) | Gets the y-coordinate of the upper-left corner of this rectangle.<br/>            Read-only **int**. |
| [`width`](/slides/python-net/aspose.slides/rectangle/width/) | Gets the width of this rectangle.<br/>            Read-only **int**. |
| [`height`](/slides/python-net/aspose.slides/rectangle/height/) | Gets the height of this rectangle.<br/>            Read-only **int**. |
| [`left`](/slides/python-net/aspose.slides/rectangle/left/) | Gets the x-coordinate of the left edge of this rectangle. Equals to `x`.<br/>            Read-only **int**. |
| [`top`](/slides/python-net/aspose.slides/rectangle/top/) | Gets the y-coordinate of the top edge of this rectangle. Equals to `y`.<br/>            Read-only **int**. |
| [`right`](/slides/python-net/aspose.slides/rectangle/right/) | Gets the x-coordinate that is the sum of `x` and `width` of this rectangle.<br/>            Read-only **int**. |
| [`bottom`](/slides/python-net/aspose.slides/rectangle/bottom/) | Gets the y-coordinate that is the sum of `y` and `height` of this rectangle.<br/>            Read-only **int**. |
| [`is_empty`](/slides/python-net/aspose.slides/rectangle/is_empty/) | Specifies whether all numeric properties of this rectangle have values of zero.<br/>            Read-only **bool**. |

## Methods

| Method | Description |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/aspose.slides/rectangle/contains/#int-int) | Determines if the specified point is contained within this rectangle. |
| [`contains(self, point)`](/slides/python-net/aspose.slides/rectangle/contains/#point) | Determines if the specified point is contained within this rectangle. |
| [`contains(self, rect)`](/slides/python-net/aspose.slides/rectangle/contains/#rectangle) | Determines if the rectangular region represented by `rect` is entirely contained within this rectangle. |


### Remarks

Rectangles are compared by their location and size with `==` and can be used as dictionary keys or set members.


### See Also
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

