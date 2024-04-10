---
title: IGeometryShape class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/
---


## IGeometryShape class

Represents the parent class for all geometric shapes.

The IGeometryShape type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [shape_style](/slides/python-net/aspose.slides/shape_style) | Returns shape's style object.<br/>            Read-only :py:class:`aspose.slides.IShapeStyle`. |
| [shape_type](/slides/python-net/aspose.slides/shape_type) | Returns or sets the geometry preset type.<br/>            Note: on value changing all adjustment values will reset to their default values.<br/>            Read/write :py:enum:`aspose.slides.ShapeType`. |
| [adjustments](/slides/python-net/aspose.slides/adjustments) | Returns a collection of shape's adjustment values.<br/>            Read-only :py:class:`aspose.slides.IAdjustValueCollection`. |
| [as_i_shape](/slides/python-net/aspose.slides/as_i_shape) | Allows to get base IShape interface.<br/>            Read-only :py:class:`aspose.slides.IShape`. |
| [is_text_holder](/slides/python-net/aspose.slides/is_text_holder) |  |
| [placeholder](/slides/python-net/aspose.slides/placeholder) |  |
| [custom_data](/slides/python-net/aspose.slides/custom_data) |  |
| [raw_frame](/slides/python-net/aspose.slides/raw_frame) |  |
| [frame](/slides/python-net/aspose.slides/frame) |  |
| [line_format](/slides/python-net/aspose.slides/line_format) |  |
| [three_d_format](/slides/python-net/aspose.slides/three_d_format) |  |
| [effect_format](/slides/python-net/aspose.slides/effect_format) |  |
| [fill_format](/slides/python-net/aspose.slides/fill_format) |  |
| [hidden](/slides/python-net/aspose.slides/hidden) |  |
| [z_order_position](/slides/python-net/aspose.slides/z_order_position) |  |
| [connection_site_count](/slides/python-net/aspose.slides/connection_site_count) |  |
| [rotation](/slides/python-net/aspose.slides/rotation) |  |
| [x](/slides/python-net/aspose.slides/x) |  |
| [y](/slides/python-net/aspose.slides/y) |  |
| [width](/slides/python-net/aspose.slides/width) |  |
| [height](/slides/python-net/aspose.slides/height) |  |
| [alternative_text](/slides/python-net/aspose.slides/alternative_text) |  |
| [alternative_text_title](/slides/python-net/aspose.slides/alternative_text_title) |  |
| [name](/slides/python-net/aspose.slides/name) |  |
| [is_decorative](/slides/python-net/aspose.slides/is_decorative) |  |
| [shape_lock](/slides/python-net/aspose.slides/shape_lock) |  |
| [unique_id](/slides/python-net/aspose.slides/unique_id) |  |
| [office_interop_shape_id](/slides/python-net/aspose.slides/office_interop_shape_id) |  |
| [is_grouped](/slides/python-net/aspose.slides/is_grouped) |  |
| [black_white_mode](/slides/python-net/aspose.slides/black_white_mode) |  |
| [parent_group](/slides/python-net/aspose.slides/parent_group) |  |
| [as_i_hyperlink_container](/slides/python-net/aspose.slides/as_i_hyperlink_container) |  |
| [as_i_slide_component](/slides/python-net/aspose.slides/as_i_slide_component) |  |
| [slide](/slides/python-net/aspose.slides/slide) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides/as_i_presentation_component) |  |
| [presentation](/slides/python-net/aspose.slides/presentation) |  |
| [hyperlink_click](/slides/python-net/aspose.slides/hyperlink_click) |  |
| [hyperlink_mouse_over](/slides/python-net/aspose.slides/hyperlink_mouse_over) |  |
| [hyperlink_manager](/slides/python-net/aspose.slides/hyperlink_manager) |  |

## Methods

| Method | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides/igeometryshape/#) |  |
| [__init__](/slides/python-net/aspose.slides/igeometryshape/#ShapeThumbnailBounds-float-float) |  |
| [__init__](/slides/python-net/aspose.slides/igeometryshape/#System.IO.Stream) |  |
| [__init__](/slides/python-net/aspose.slides/igeometryshape/#System.IO.Stream-aspose.slides.export.ISVGOptions) |  |
| [__init__](/slides/python-net/aspose.slides/igeometryshape/#) | Returns the copy of path of the geometry shape. Coordinates are relative to the left top corner of the shape. |
| [__init__](/slides/python-net/aspose.slides/igeometryshape/#IGeometryPath) | Updates shape geometry from :py:class:`aspose.slides.IGeometryPath` object. Coordinates must be relative to the left<br/>             top corner of the shape.<br/>             Changes the type of the shape (:py:attr:`aspose.slides.IGeometryShape.shape_type`) to :py:attr:`aspose.slides.ShapeType.CUSTOM`. |
| [__init__](/slides/python-net/aspose.slides/igeometryshape/#List[IGeometryPath]) | Updates shape geometry from array of :py:class:`aspose.slides.IGeometryPath`. Coordinates must be relative to the left<br/>             top corner of the shape.<br/>             Changes the type of the shape (:py:attr:`aspose.slides.IGeometryShape.shape_type`) to :py:attr:`aspose.slides.ShapeType.CUSTOM`. |
| [__init__](/slides/python-net/aspose.slides/igeometryshape/#) | Creates and returns array of shape's elements. |
| [__init__](/slides/python-net/aspose.slides/igeometryshape/#IPlaceholder) |  |
| [__init__](/slides/python-net/aspose.slides/igeometryshape/#) |  |
| [__init__](/slides/python-net/aspose.slides/igeometryshape/#) |  |

