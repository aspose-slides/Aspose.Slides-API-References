---
title: ShapeUtil
type: docs
weight: 0
url: /php-java/shapeutil/
---

# ShapeUtil class

 Offer methods which helps to process shapes objects.
 

## Constructors

| name | description |
| --- | --- |
| [ShapeUtil](/slides/php-java/shapeutil/shapeutil/)() |  |

## Methods

| name | return type | description |
| --- | --- | --- |
| [geometryPathToGraphicsPath](/slides/php-java/shapeutil/geometrypathtographicspath/)(IGeometryPath) | Shape | Converts IGeometryPath to java.awt.Shape. GraphicsPath can be transformed in a different ways using its convenient methods and then transformed back into the IGeometryPath to use in GeometryShape via #graphicsPathToGeometryPath(java.awt.Shape graphicsPath) method. |
| [graphicsPathToGeometryPath](/slides/php-java/shapeutil/graphicspathtogeometrypath/)(Shape) | IGeometryPath | Converts a java.awt.Shape graphicsPath to the IGeometryPath |
