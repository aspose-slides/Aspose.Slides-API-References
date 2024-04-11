---
title: IAutoShape
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/iautoshape/
---


IAutoShape class

Represents an AutoShape.

The IAutoShape type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [shape_lock](/slides/python-net/aspose.slides/iautoshape/shape_lock/) | Returns shape's locks.<br/>            Read-only <br/>[`IAutoShapeLock`](/slides/python-net/aspose.slides/iautoshapelock). |
| [auto_shape_lock](/slides/python-net/aspose.slides/iautoshape/auto_shape_lock/) | Returns AutoShape's locks.<br/>            Read-only <br/>[`IAutoShapeLock`](/slides/python-net/aspose.slides/iautoshapelock). |
| [text_frame](/slides/python-net/aspose.slides/iautoshape/text_frame/) | Returns TextFrameEx object for the AutoShapeEx.<br/>            Read-only <br/>[`ITextFrame`](/slides/python-net/aspose.slides/itextframe). |
| [use_background_fill](/slides/python-net/aspose.slides/iautoshape/use_background_fill/) | Determines whether this autoshape should be filled with slide's background fill instead of specified by style or fill format.<br/>            Read/write <br/>.NET type System.Boolean. |
| [is_text_box](/slides/python-net/aspose.slides/iautoshape/is_text_box/) | Specifies if the shape is a text box. |
| [as_i_geometry_shape](/slides/python-net/aspose.slides/iautoshape/as_i_geometry_shape/) | Allows to get base IGeometryShape interface.<br/>            Read-only <br/>[`IGeometryShape`](/slides/python-net/aspose.slides/igeometryshape). |
| [shape_style](/slides/python-net/aspose.slides/iautoshape/shape_style/) |  |
| [shape_type](/slides/python-net/aspose.slides/iautoshape/shape_type/) |  |
| [adjustments](/slides/python-net/aspose.slides/iautoshape/adjustments/) |  |
| [as_i_shape](/slides/python-net/aspose.slides/iautoshape/as_i_shape/) |  |
| [is_text_holder](/slides/python-net/aspose.slides/iautoshape/is_text_holder/) |  |
| [placeholder](/slides/python-net/aspose.slides/iautoshape/placeholder/) |  |
| [custom_data](/slides/python-net/aspose.slides/iautoshape/custom_data/) |  |
| [raw_frame](/slides/python-net/aspose.slides/iautoshape/raw_frame/) |  |
| [frame](/slides/python-net/aspose.slides/iautoshape/frame/) |  |
| [line_format](/slides/python-net/aspose.slides/iautoshape/line_format/) |  |
| [three_d_format](/slides/python-net/aspose.slides/iautoshape/three_d_format/) |  |
| [effect_format](/slides/python-net/aspose.slides/iautoshape/effect_format/) |  |
| [fill_format](/slides/python-net/aspose.slides/iautoshape/fill_format/) |  |
| [hidden](/slides/python-net/aspose.slides/iautoshape/hidden/) |  |
| [z_order_position](/slides/python-net/aspose.slides/iautoshape/z_order_position/) |  |
| [connection_site_count](/slides/python-net/aspose.slides/iautoshape/connection_site_count/) |  |
| [rotation](/slides/python-net/aspose.slides/iautoshape/rotation/) |  |
| [x](/slides/python-net/aspose.slides/iautoshape/x/) |  |
| [y](/slides/python-net/aspose.slides/iautoshape/y/) |  |
| [width](/slides/python-net/aspose.slides/iautoshape/width/) |  |
| [height](/slides/python-net/aspose.slides/iautoshape/height/) |  |
| [alternative_text](/slides/python-net/aspose.slides/iautoshape/alternative_text/) |  |
| [alternative_text_title](/slides/python-net/aspose.slides/iautoshape/alternative_text_title/) |  |
| [name](/slides/python-net/aspose.slides/iautoshape/name/) |  |
| [is_decorative](/slides/python-net/aspose.slides/iautoshape/is_decorative/) |  |
| [unique_id](/slides/python-net/aspose.slides/iautoshape/unique_id/) |  |
| [office_interop_shape_id](/slides/python-net/aspose.slides/iautoshape/office_interop_shape_id/) |  |
| [is_grouped](/slides/python-net/aspose.slides/iautoshape/is_grouped/) |  |
| [black_white_mode](/slides/python-net/aspose.slides/iautoshape/black_white_mode/) |  |
| [parent_group](/slides/python-net/aspose.slides/iautoshape/parent_group/) |  |
| [as_i_hyperlink_container](/slides/python-net/aspose.slides/iautoshape/as_i_hyperlink_container/) |  |
| [as_i_slide_component](/slides/python-net/aspose.slides/iautoshape/as_i_slide_component/) |  |
| [slide](/slides/python-net/aspose.slides/iautoshape/slide/) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides/iautoshape/as_i_presentation_component/) |  |
| [presentation](/slides/python-net/aspose.slides/iautoshape/presentation/) |  |
| [hyperlink_click](/slides/python-net/aspose.slides/iautoshape/hyperlink_click/) |  |
| [hyperlink_mouse_over](/slides/python-net/aspose.slides/iautoshape/hyperlink_mouse_over/) |  |
| [hyperlink_manager](/slides/python-net/aspose.slides/iautoshape/hyperlink_manager/) |  |

## Methods

| Method | Description |
| :- | :- |
| [get_thumbnail](/slides/python-net/aspose.slides/iautoshape/iautoshape/#/) |  |
| [get_thumbnail](/slides/python-net/aspose.slides/iautoshape/iautoshape/#ShapeThumbnailBounds-float-float/) |  |
| [write_as_svg](/slides/python-net/aspose.slides/iautoshape/iautoshape/#System.IO.Stream/) |  |
| [write_as_svg](/slides/python-net/aspose.slides/iautoshape/iautoshape/#System.IO.Stream-aspose.slides.export.ISVGOptions/) |  |
| [add_text_frame](/slides/python-net/aspose.slides/iautoshape/iautoshape/#string/) | Adds a new TextFrameEx to a shape.<br/>            If shape already has TextFrameEx then simply changes its text. |
| [get_geometry_paths](/slides/python-net/aspose.slides/iautoshape/iautoshape/#/) |  |
| [set_geometry_path](/slides/python-net/aspose.slides/iautoshape/iautoshape/#IGeometryPath/) |  |
| [set_geometry_paths](/slides/python-net/aspose.slides/iautoshape/iautoshape/#List[IGeometryPath]/) |  |
| [create_shape_elements](/slides/python-net/aspose.slides/iautoshape/iautoshape/#/) |  |
| [add_placeholder](/slides/python-net/aspose.slides/iautoshape/iautoshape/#IPlaceholder/) |  |
| [remove_placeholder](/slides/python-net/aspose.slides/iautoshape/iautoshape/#/) |  |
| [get_base_placeholder](/slides/python-net/aspose.slides/iautoshape/iautoshape/#/) |  |

