---
title: IShape
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ishape/
---


IShape class

Represents a shape on a slide.

The IShape type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [is_text_holder](/slides/python-net/aspose.slides/ishape/is_text_holder/) | Determines whether the shape is TextHolder.<br/>            Read-only <br/>.NET type System.Boolean. |
| [placeholder](/slides/python-net/aspose.slides/ishape/placeholder/) | Returns the placeholder for a shape.<br/>            Read-only <br/>[`IPlaceholder`](/slides/python-net/aspose.slides/iplaceholder). |
| [custom_data](/slides/python-net/aspose.slides/ishape/custom_data/) | Returns the shape's custom data.<br/>            Read-only <br/>[`ICustomData`](/slides/python-net/aspose.slides/icustomdata). |
| [raw_frame](/slides/python-net/aspose.slides/ishape/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            Read/write <br/>[`IShapeFrame`](/slides/python-net/aspose.slides/ishapeframe). |
| [frame](/slides/python-net/aspose.slides/ishape/frame/) | Returns or sets the shape frame's properties.<br/>            Read/write <br/>[`IShapeFrame`](/slides/python-net/aspose.slides/ishapeframe). |
| [line_format](/slides/python-net/aspose.slides/ishape/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Read-only <br/>[`ILineFormat`](/slides/python-net/aspose.slides/ilineformat). |
| [three_d_format](/slides/python-net/aspose.slides/ishape/three_d_format/) | Returns the ThreeDFormat object that contains line formatting properties for a shape.<br/>            Read-only <br/>[`IThreeDFormat`](/slides/python-net/aspose.slides/ithreedformat). |
| [effect_format](/slides/python-net/aspose.slides/ishape/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Read-only <br/>[`IEffectFormat`](/slides/python-net/aspose.slides/ieffectformat). |
| [fill_format](/slides/python-net/aspose.slides/ishape/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Read-only <br/>[`IFillFormat`](/slides/python-net/aspose.slides/ifillformat). |
| [hidden](/slides/python-net/aspose.slides/ishape/hidden/) | Determines whether the shape is hidden.<br/>            Read/write <br/>.NET type System.Boolean. |
| [z_order_position](/slides/python-net/aspose.slides/ishape/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Read-only <br/>.NET type System.Int32. |
| [connection_site_count](/slides/python-net/aspose.slides/ishape/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            Read-only <br/>.NET type System.Int32. |
| [rotation](/slides/python-net/aspose.slides/ishape/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Read/write <br/>.NET type System.Single. |
| [x](/slides/python-net/aspose.slides/ishape/x/) | Returns or sets the x-coordinate of the upper-left corner of the shape.<br/>            Read/write <br/>.NET type System.Single. |
| [y](/slides/python-net/aspose.slides/ishape/y/) | Returns or sets the y-coordinate of the upper-left corner of the shape.<br/>            Read/write <br/>.NET type System.Single. |
| [width](/slides/python-net/aspose.slides/ishape/width/) | Returns or sets the width of the shape.<br/>            Read/write <br/>.NET type System.Single. |
| [height](/slides/python-net/aspose.slides/ishape/height/) | Returns or sets the height of the shape.<br/>            Read/write <br/>.NET type System.Single. |
| [alternative_text](/slides/python-net/aspose.slides/ishape/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            Read/write <br/>.NET type System.String. |
| [alternative_text_title](/slides/python-net/aspose.slides/ishape/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            Read/write <br/>.NET type System.String. |
| [name](/slides/python-net/aspose.slides/ishape/name/) | Returns or sets the name of a shape.<br/>            Read/write <br/>.NET type System.String. |
| [is_decorative](/slides/python-net/aspose.slides/ishape/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Reed/write <br/>.NET type System.Boolean. |
| [shape_lock](/slides/python-net/aspose.slides/ishape/shape_lock/) | Returns shape's locks.<br/>            Read-only <br/>[`IBaseShapeLock`](/slides/python-net/aspose.slides/ibaseshapelock). |
| [unique_id](/slides/python-net/aspose.slides/ishape/unique_id/) | Gets unique shape identifier in presentation scope.<br/>            Read-only <br/>.NET type System.UInt32.<br/>            See also <br/>[`IShape.office_interop_shape_id`](/slides/python-net/aspose.slides/ishape#office_interop_shape_id) for getting unique shape identifier in slide scope. |
| [office_interop_shape_id](/slides/python-net/aspose.slides/ishape/office_interop_shape_id/) | Gets unique shape identifier in slide scope.<br/>            Read-only <br/>.NET type System.UInt32.<br/>            See also <br/>[`IShape.unique_id`](/slides/python-net/aspose.slides/ishape#unique_id) for getting unique shape identifier in presentation scope. |
| [is_grouped](/slides/python-net/aspose.slides/ishape/is_grouped/) | Determines whether the shape is grouped.<br/>            Read-only <br/>.NET type System.Boolean. |
| [black_white_mode](/slides/python-net/aspose.slides/ishape/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            Read/write <br/>[`BlackWhiteMode`](/slides/python-net/aspose.slides/blackwhitemode). |
| [parent_group](/slides/python-net/aspose.slides/ishape/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns null.<br/>            Read-only <br/>[`IGroupShape`](/slides/python-net/aspose.slides/igroupshape). |
| [as_i_hyperlink_container](/slides/python-net/aspose.slides/ishape/as_i_hyperlink_container/) | Allows to get base IHyperlinkContainer interface.<br/>            Read-only <br/>[`IHyperlinkContainer`](/slides/python-net/aspose.slides/ihyperlinkcontainer). |
| [as_i_slide_component](/slides/python-net/aspose.slides/ishape/as_i_slide_component/) | Allows to get base ISlideComponent interface.<br/>            Read-only <br/>[`ISlideComponent`](/slides/python-net/aspose.slides/islidecomponent). |
| [slide](/slides/python-net/aspose.slides/ishape/slide/) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides/ishape/as_i_presentation_component/) |  |
| [presentation](/slides/python-net/aspose.slides/ishape/presentation/) |  |
| [hyperlink_click](/slides/python-net/aspose.slides/ishape/hyperlink_click/) |  |
| [hyperlink_mouse_over](/slides/python-net/aspose.slides/ishape/hyperlink_mouse_over/) |  |
| [hyperlink_manager](/slides/python-net/aspose.slides/ishape/hyperlink_manager/) |  |

## Methods

| Method | Description |
| :- | :- |
| [get_thumbnail](/slides/python-net/aspose.slides/ishape/ishape/#/) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [get_thumbnail](/slides/python-net/aspose.slides/ishape/ishape/#ShapeThumbnailBounds-float-float/) | Returns shape thumbnail. |
| [write_as_svg](/slides/python-net/aspose.slides/ishape/ishape/#System.IO.Stream/) | Saves content of Shape as SVG file. |
| [write_as_svg](/slides/python-net/aspose.slides/ishape/ishape/#System.IO.Stream-aspose.slides.export.ISVGOptions/) | Saves content of Shape as SVG file. |
| [add_placeholder](/slides/python-net/aspose.slides/ishape/ishape/#IPlaceholder/) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [remove_placeholder](/slides/python-net/aspose.slides/ishape/ishape/#/) | Defines that this shape isn't a placeholder. |
| [get_base_placeholder](/slides/python-net/aspose.slides/ishape/ishape/#/) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            <br/>A null is returned if the current shape is not inherited. |

