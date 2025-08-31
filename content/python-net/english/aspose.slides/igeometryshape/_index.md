---
title: IGeometryShape class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/igeometryshape/
---


## IGeometryShape class

Represents the parent class for all geometric shapes.

The IGeometryShape type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`shape_style`](/slides/python-net/aspose.slides/igeometryshape/shape_style/) | Returns shape's style object.<br/>            Read-only [`IShapeStyle`](/slides/python-net/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/aspose.slides/igeometryshape/shape_type/) | Returns or sets the geometry preset type.<br/>            Note: on value changing all adjustment values will reset to their default values.<br/>            Read/write [`ShapeType`](/slides/python-net/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/aspose.slides/igeometryshape/adjustments/) | Returns a collection of shape's adjustment values.<br/>            Read-only [`IAdjustValueCollection`](/slides/python-net/aspose.slides/iadjustvaluecollection). |

## Methods

| Method | Description |
| :- | :- |
| [`get_geometry_paths`](/slides/python-net/aspose.slides/igeometryshape/get_geometry_paths/#) | Returns the copy of path of the geometry shape. Coordinates are relative to the left top corner of the shape. |
| [`set_geometry_path`](/slides/python-net/aspose.slides/igeometryshape/set_geometry_path/#asposeslidesigeometrypath) | Updates shape geometry from [`IGeometryPath`](/slides/python-net/aspose.slides/igeometrypath) object. Coordinates must be relative to the left<br/>             top corner of the shape.<br/>             Changes the type of the shape ([`IGeometryShape.shape_type`](/slides/python-net/aspose.slides/igeometryshape/shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths`](/slides/python-net/aspose.slides/igeometryshape/set_geometry_paths/#listasposeslidesigeometrypath) | Updates shape geometry from array of [`IGeometryPath`](/slides/python-net/aspose.slides/igeometrypath). Coordinates must be relative to the left<br/>             top corner of the shape.<br/>             Changes the type of the shape ([`IGeometryShape.shape_type`](/slides/python-net/aspose.slides/igeometryshape/shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements`](/slides/python-net/aspose.slides/igeometryshape/create_shape_elements/#) | Creates and returns array of shape's elements. |


### See Also
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

