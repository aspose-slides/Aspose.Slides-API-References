---
title: IShape class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/
---


## IShape class

Represents a shape on a slide.

The IShape type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [is_text_holder](/slides/python-net/aspose.slides/is_text_holder) | Determines whether the shape is TextHolder.<br/>            Read-only :py:class:`bool`. |
| [placeholder](/slides/python-net/aspose.slides/placeholder) | Returns the placeholder for a shape.<br/>            Read-only :py:class:`aspose.slides.IPlaceholder`. |
| [custom_data](/slides/python-net/aspose.slides/custom_data) | Returns the shape's custom data.<br/>            Read-only :py:class:`aspose.slides.ICustomData`. |
| [raw_frame](/slides/python-net/aspose.slides/raw_frame) | Returns or sets the raw shape frame's properties.<br/>            Read/write :py:class:`aspose.slides.IShapeFrame`. |
| [frame](/slides/python-net/aspose.slides/frame) | Returns or sets the shape frame's properties.<br/>            Read/write :py:class:`aspose.slides.IShapeFrame`. |
| [line_format](/slides/python-net/aspose.slides/line_format) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Read-only :py:class:`aspose.slides.ILineFormat`. |
| [three_d_format](/slides/python-net/aspose.slides/three_d_format) | Returns the ThreeDFormat object that contains line formatting properties for a shape.<br/>            Read-only :py:class:`aspose.slides.IThreeDFormat`. |
| [effect_format](/slides/python-net/aspose.slides/effect_format) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Read-only :py:class:`aspose.slides.IEffectFormat`. |
| [fill_format](/slides/python-net/aspose.slides/fill_format) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Read-only :py:class:`aspose.slides.IFillFormat`. |
| [hidden](/slides/python-net/aspose.slides/hidden) | Determines whether the shape is hidden.<br/>            Read/write :py:class:`bool`. |
| [z_order_position](/slides/python-net/aspose.slides/z_order_position) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Read-only :py:class:`int`. |
| [connection_site_count](/slides/python-net/aspose.slides/connection_site_count) | Returns the number of connection sites on the shape.<br/>            Read-only :py:class:`int`. |
| [rotation](/slides/python-net/aspose.slides/rotation) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Read/write :py:class:`float`. |
| [x](/slides/python-net/aspose.slides/x) | Returns or sets the x-coordinate of the upper-left corner of the shape.<br/>            Read/write :py:class:`float`. |
| [y](/slides/python-net/aspose.slides/y) | Returns or sets the y-coordinate of the upper-left corner of the shape.<br/>            Read/write :py:class:`float`. |
| [width](/slides/python-net/aspose.slides/width) | Returns or sets the width of the shape.<br/>            Read/write :py:class:`float`. |
| [height](/slides/python-net/aspose.slides/height) | Returns or sets the height of the shape.<br/>            Read/write :py:class:`float`. |
| [alternative_text](/slides/python-net/aspose.slides/alternative_text) | Returns or sets the alternative text associated with a shape.<br/>            Read/write :py:class:`System.String`. |
| [alternative_text_title](/slides/python-net/aspose.slides/alternative_text_title) | Returns or sets the title of alternative text associated with a shape.<br/>            Read/write :py:class:`System.String`. |
| [name](/slides/python-net/aspose.slides/name) | Returns or sets the name of a shape.<br/>            Read/write :py:class:`System.String`. |
| [is_decorative](/slides/python-net/aspose.slides/is_decorative) | Gets or sets 'Mark as decorative' option<br/>            Reed/write :py:class:`bool`. |
| [shape_lock](/slides/python-net/aspose.slides/shape_lock) | Returns shape's locks.<br/>            Read-only :py:class:`aspose.slides.IBaseShapeLock`. |
| [unique_id](/slides/python-net/aspose.slides/unique_id) | Gets unique shape identifier in presentation scope.<br/>            Read-only :py:class:`int`.<br/>            See also :py:attr:`aspose.slides.IShape.office_interop_shape_id` for getting unique shape identifier in slide scope. |
| [office_interop_shape_id](/slides/python-net/aspose.slides/office_interop_shape_id) | Gets unique shape identifier in slide scope.<br/>            Read-only :py:class:`int`.<br/>            See also :py:attr:`aspose.slides.IShape.unique_id` for getting unique shape identifier in presentation scope. |
| [is_grouped](/slides/python-net/aspose.slides/is_grouped) | Determines whether the shape is grouped.<br/>            Read-only :py:class:`bool`. |
| [black_white_mode](/slides/python-net/aspose.slides/black_white_mode) | Property specifies how a shape will render in black-and-white display mode..<br/>            Read/write :py:enum:`aspose.slides.BlackWhiteMode`. |
| [parent_group](/slides/python-net/aspose.slides/parent_group) | Returns parent GroupShape object if shape is grouped. Otherwise returns null.<br/>            Read-only :py:class:`aspose.slides.IGroupShape`. |
| [as_i_hyperlink_container](/slides/python-net/aspose.slides/as_i_hyperlink_container) | Allows to get base IHyperlinkContainer interface.<br/>            Read-only :py:class:`aspose.slides.IHyperlinkContainer`. |
| [as_i_slide_component](/slides/python-net/aspose.slides/as_i_slide_component) | Allows to get base ISlideComponent interface.<br/>            Read-only :py:class:`aspose.slides.ISlideComponent`. |
| [slide](/slides/python-net/aspose.slides/slide) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides/as_i_presentation_component) |  |
| [presentation](/slides/python-net/aspose.slides/presentation) |  |
| [hyperlink_click](/slides/python-net/aspose.slides/hyperlink_click) |  |
| [hyperlink_mouse_over](/slides/python-net/aspose.slides/hyperlink_mouse_over) |  |
| [hyperlink_manager](/slides/python-net/aspose.slides/hyperlink_manager) |  |

## Methods

| Method | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides/ishape/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [__init__](/slides/python-net/aspose.slides/ishape/#ShapeThumbnailBounds-float-float) | Returns shape thumbnail. |
| [__init__](/slides/python-net/aspose.slides/ishape/#System.IO.Stream) | Saves content of Shape as SVG file. |
| [__init__](/slides/python-net/aspose.slides/ishape/#System.IO.Stream-aspose.slides.export.ISVGOptions) | Saves content of Shape as SVG file. |
| [__init__](/slides/python-net/aspose.slides/ishape/#IPlaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [__init__](/slides/python-net/aspose.slides/ishape/#) | Defines that this shape isn't a placeholder. |
| [__init__](/slides/python-net/aspose.slides/ishape/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from). |

