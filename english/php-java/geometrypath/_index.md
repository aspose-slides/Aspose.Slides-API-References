---
title: GeometryPath
type: docs
weight: 0
url: /php-java/geometrypath/
---

# GeometryPath class

 Represents geometry path of GeometryShape
 

## Constructors

| name | description |
| --- | --- |
| [GeometryPath](/slides/php-java/geometrypath/geometrypath/)() | Creates instance of GeometryPath |

## Methods

| name | return type | description |
| --- | --- | --- |
| [arcTo](/slides/php-java/geometrypath/arcto/)(float, float, float, float) | void | Appends the specified arc to the path. |
| [closeFigure](/slides/php-java/geometrypath/closefigure/)() | void | Closes the current figure of this path |
| [cubicBezierTo](/slides/php-java/geometrypath/cubicbezierto/)(Point2D.Float, Point2D.Float, Point2D.Float) | void | Adds cubic Bezier curve at the end the path |
| [cubicBezierTo](/slides/php-java/geometrypath/cubicbezierto/)(float, float, float, float, float, float) | void | Adds cubic Bezier curve at the end the path |
| [cubicBezierTo](/slides/php-java/geometrypath/cubicbezierto/)(Point2D.Float, Point2D.Float, Point2D.Float, long) | void | Adds cubic Bezier curve to the specified place of the path |
| [cubicBezierTo](/slides/php-java/geometrypath/cubicbezierto/)(float, float, float, float, float, float, long) | void | Adds cubic Bezier curve to the specified place of the path |
| [getFillMode](/slides/php-java/geometrypath/getfillmode/)() | byte | Sets fill mode |
| [getPathData](/slides/php-java/geometrypath/getpathdata/)() | IPathSegment | Returns geometry path of GeometryShape as an array of path segments. |
| [getStroke](/slides/php-java/geometrypath/getstroke/)() | boolean | Sets stroke appearance |
| [lineTo](/slides/php-java/geometrypath/lineto/)(Point2D.Float) | void | Adds line to the end of the path |
| [lineTo](/slides/php-java/geometrypath/lineto/)(float, float) | void | Adds line to the end of the path |
| [lineTo](/slides/php-java/geometrypath/lineto/)(Point2D.Float, long) | void | Adds line to the specified place of the path |
| [lineTo](/slides/php-java/geometrypath/lineto/)(float, float, long) | void | Adds line to the specified place of the path |
| [moveTo](/slides/php-java/geometrypath/moveto/)(Point2D.Float) | void | Sets next point position. |
| [moveTo](/slides/php-java/geometrypath/moveto/)(float, float) | void | Sets next point position. |
| [quadraticBezierTo](/slides/php-java/geometrypath/quadraticbezierto/)(Point2D.Float, Point2D.Float) | void | Adds quadratic Bezier curve at the end the path |
| [quadraticBezierTo](/slides/php-java/geometrypath/quadraticbezierto/)(float, float, float, float) | void | Adds quadratic Bezier curve at the end the path |
| [quadraticBezierTo](/slides/php-java/geometrypath/quadraticbezierto/)(Point2D.Float, Point2D.Float, long) | void | Adds quadratic Bezier curve to the specified place of the path |
| [quadraticBezierTo](/slides/php-java/geometrypath/quadraticbezierto/)(float, float, float, float, long) | void | Adds quadratic Bezier curve to the specified place of the path |
| [removeAt](/slides/php-java/geometrypath/removeat/)(int) | void | Removes segment at the specified index of the geometry path. |
| [setFillMode](/slides/php-java/geometrypath/setfillmode/)(byte) | void | Sets fill mode |
| [setStroke](/slides/php-java/geometrypath/setstroke/)(boolean) | void | Sets stroke appearance |
