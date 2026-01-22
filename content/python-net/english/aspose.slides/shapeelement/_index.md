---
title: ShapeElement class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapeelement/
---


## ShapeElement class

Represents a part of shape with same outline and fill properties.

The ShapeElement type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`parent_shape`](/slides/python-net/aspose.slides/shapeelement/parent_shape/) | Returns a Shape_PPT for which element was created.<br/>            Read-only [`Shape`](/slides/python-net/aspose.slides/shape). |
| [`path_points`](/slides/python-net/aspose.slides/shapeelement/path_points/) | Gets an array of points that define the geometry of the element's path. |
| [`path_types`](/slides/python-net/aspose.slides/shapeelement/path_types/) | Gets an array of byte values that specify the type of each point in the element's path. <br/>            <br/>**0**  Indicates that the point is the start of a figure.<br/><br/><br/>**1**  Indicates that the point is one of the two endpoints of a line.<br/><br/><br/>**3**  Indicates that the point is an endpoint or control point of a cubic Bezier spline.<br/><br/><br/>**7**  Masks all bits except for the three low-order bits, which indicate the point type.<br/><br/><br/>**16**  Specifies that the corresponding segment is dashed.<br/><br/><br/>**32**  Specifies that the point is a marker.<br/><br/><br/>**128**  Specifies that the point is the last point in a closed subpath (figure).<br/><br/><br/>**129**  Indicates a data point that is both a line segment endpoint and the last point of a closed subpath. |
| [`fill_source`](/slides/python-net/aspose.slides/shapeelement/fill_source/) | Returns information about how to fill an element.<br/>            Read-only [`ShapeElementFillSource`](/slides/python-net/aspose.slides/shapeelementfillsource). |
| [`stroke_source`](/slides/python-net/aspose.slides/shapeelement/stroke_source/) | Returns information about how to stroke an element.<br/>            Read-only [`ShapeElementStrokeSource`](/slides/python-net/aspose.slides/shapeelementstrokesource). |


### See Also
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

