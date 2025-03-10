﻿---
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
| [`is_text_holder`](/slides/python-net/aspose.slides/igeometryshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/aspose.slides/igeometryshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/aspose.slides/igeometryshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/aspose.slides/igeometryshape/raw_frame/) |  |
| [`frame`](/slides/python-net/aspose.slides/igeometryshape/frame/) |  |
| [`line_format`](/slides/python-net/aspose.slides/igeometryshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/aspose.slides/igeometryshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/aspose.slides/igeometryshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/aspose.slides/igeometryshape/fill_format/) |  |
| [`hidden`](/slides/python-net/aspose.slides/igeometryshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/aspose.slides/igeometryshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/aspose.slides/igeometryshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/aspose.slides/igeometryshape/rotation/) |  |
| [`x`](/slides/python-net/aspose.slides/igeometryshape/x/) |  |
| [`y`](/slides/python-net/aspose.slides/igeometryshape/y/) |  |
| [`width`](/slides/python-net/aspose.slides/igeometryshape/width/) |  |
| [`height`](/slides/python-net/aspose.slides/igeometryshape/height/) |  |
| [`alternative_text`](/slides/python-net/aspose.slides/igeometryshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/aspose.slides/igeometryshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/aspose.slides/igeometryshape/name/) |  |
| [`is_decorative`](/slides/python-net/aspose.slides/igeometryshape/is_decorative/) |  |
| [`shape_lock`](/slides/python-net/aspose.slides/igeometryshape/shape_lock/) |  |
| [`unique_id`](/slides/python-net/aspose.slides/igeometryshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/aspose.slides/igeometryshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/aspose.slides/igeometryshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/aspose.slides/igeometryshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/aspose.slides/igeometryshape/parent_group/) |  |
| [`slide`](/slides/python-net/aspose.slides/igeometryshape/slide/) |  |
| [`presentation`](/slides/python-net/aspose.slides/igeometryshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/aspose.slides/igeometryshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/aspose.slides/igeometryshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/aspose.slides/igeometryshape/hyperlink_manager/) |  |

## Methods

| Method | Description |
| :- | :- |
| [`get_thumbnail`](/slides/python-net/aspose.slides/igeometryshape/get_thumbnail/#) |  |
| [`get_thumbnail`](/slides/python-net/aspose.slides/igeometryshape/get_thumbnail/#shapethumbnailbounds-float-float) |  |
| [`get_image`](/slides/python-net/aspose.slides/igeometryshape/get_image/#) |  |
| [`get_image`](/slides/python-net/aspose.slides/igeometryshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg`](/slides/python-net/aspose.slides/igeometryshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg`](/slides/python-net/aspose.slides/igeometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths`](/slides/python-net/aspose.slides/igeometryshape/get_geometry_paths/#) | Returns the copy of path of the geometry shape. Coordinates are relative to the left top corner of the shape. |
| [`set_geometry_path`](/slides/python-net/aspose.slides/igeometryshape/set_geometry_path/#igeometrypath) | Updates shape geometry from [`IGeometryPath`](/slides/python-net/aspose.slides/igeometrypath) object. Coordinates must be relative to the left<br/>             top corner of the shape.<br/>             Changes the type of the shape ([`IGeometryShape.shape_type`](/slides/python-net/aspose.slides/igeometryshape/shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths`](/slides/python-net/aspose.slides/igeometryshape/set_geometry_paths/#listigeometrypath) | Updates shape geometry from array of [`IGeometryPath`](/slides/python-net/aspose.slides/igeometrypath). Coordinates must be relative to the left<br/>             top corner of the shape.<br/>             Changes the type of the shape ([`IGeometryShape.shape_type`](/slides/python-net/aspose.slides/igeometryshape/shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements`](/slides/python-net/aspose.slides/igeometryshape/create_shape_elements/#) | Creates and returns array of shape's elements. |
| [`add_placeholder`](/slides/python-net/aspose.slides/igeometryshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder`](/slides/python-net/aspose.slides/igeometryshape/remove_placeholder/#) |  |
| [`get_base_placeholder`](/slides/python-net/aspose.slides/igeometryshape/get_base_placeholder/#) |  |


### See Also
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

