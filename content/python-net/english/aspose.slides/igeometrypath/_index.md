---
title: IGeometryPath class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/igeometrypath/
---


## IGeometryPath class

Represents geometry path of GeometryShape

The IGeometryPath type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`path_data`](/slides/python-net/aspose.slides/igeometrypath/path_data/) | Returns geometry path of GeometryShape as an array of path segments. |
| [`fill_mode`](/slides/python-net/aspose.slides/igeometrypath/fill_mode/) | Sets fill mode |
| [`stroke`](/slides/python-net/aspose.slides/igeometrypath/stroke/) | Sets stroke appearance |

## Methods

| Method | Description |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/aspose.slides/igeometrypath/line_to/#asposepydrawingpointf) | Adds line to the end of the path |
| [`line_to(self, x, y)`](/slides/python-net/aspose.slides/igeometrypath/line_to/#float-float) | Adds line to the end of the path |
| [`line_to(self, point, index)`](/slides/python-net/aspose.slides/igeometrypath/line_to/#asposepydrawingpointf-int) | Adds line to the specified place of the path |
| [`line_to(self, x, y, index)`](/slides/python-net/aspose.slides/igeometrypath/line_to/#float-float-int) | Adds line to the specified place of the path |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/aspose.slides/igeometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf) | Adds cubic Bezier curve at the end the path |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Adds cubic Bezier curve at the end the path |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/aspose.slides/igeometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int) | Adds cubic Bezier curve to the specified place of the path |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Adds cubic Bezier curve to the specified place of the path |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/aspose.slides/igeometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf) | Adds quadratic Bezier curve at the end the path |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float) | Adds quadratic Bezier curve at the end the path |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/aspose.slides/igeometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-int) | Adds quadratic Bezier curve to the specified place of the path |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float-int) | Adds quadratic Bezier curve to the specified place of the path |
| [`move_to(self, point)`](/slides/python-net/aspose.slides/igeometrypath/move_to/#asposepydrawingpointf) | Sets next point position. |
| [`move_to(self, x, y)`](/slides/python-net/aspose.slides/igeometrypath/move_to/#float-float) | Sets next point position. |
| [`remove_at(self, index)`](/slides/python-net/aspose.slides/igeometrypath/remove_at/#int) | Removes segment at the specified index of the geometry path. |
| [`close_figure(self)`](/slides/python-net/aspose.slides/igeometrypath/close_figure/#) | Closes the current figure of this path |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/aspose.slides/igeometrypath/arc_to/#float-float-float-float) | Appends the specified arc to the path. |


### See Also
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

