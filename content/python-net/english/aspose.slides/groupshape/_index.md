---
title: GroupShape
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/groupshape/
---


GroupShape class

Represents a group of shapes on a slide.

**Inheritance:**[`GroupShape`](/slides/python-net/aspose.slides/groupshape) → [`Shape`](/slides/python-net/aspose.slides/shape)

The GroupShape type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [is_text_holder](/slides/python-net/aspose.slides/groupshape/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            Read-only :py:class:`bool`. |
| [placeholder](/slides/python-net/aspose.slides/groupshape/placeholder/) | Returns the placeholder for a shape. Returns null if the shape has no placeholder.<br/>            Read-only :py:class:`aspose.slides.IPlaceholder`. |
| [custom_data](/slides/python-net/aspose.slides/groupshape/custom_data/) | Returns the shape's custom data.<br/>            Read-only :py:class:`aspose.slides.ICustomData`. |
| [raw_frame](/slides/python-net/aspose.slides/groupshape/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            Read/write :py:class:`aspose.slides.IShapeFrame`. |
| [frame](/slides/python-net/aspose.slides/groupshape/frame/) | Returns or sets the shape frame's properties.<br/>            Read/write :py:class:`aspose.slides.IShapeFrame`. |
| [line_format](/slides/python-net/aspose.slides/groupshape/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Note: Returns null for GroupShape objects because they don't have line properties.<br/>            Read-only :py:class:`aspose.slides.ILineFormat`. |
| [three_d_format](/slides/python-net/aspose.slides/groupshape/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have 3d properties.<br/>            Read-only :py:class:`aspose.slides.IThreeDFormat`. |
| [effect_format](/slides/python-net/aspose.slides/groupshape/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Note: can return null for certain types of shapes which don't have effect properties.<br/>            Read-only :py:class:`aspose.slides.IEffectFormat`. |
| [fill_format](/slides/python-net/aspose.slides/groupshape/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have fill properties.<br/>            Read-only :py:class:`aspose.slides.IFillFormat`. |
| [hyperlink_click](/slides/python-net/aspose.slides/groupshape/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            Read/write :py:class:`aspose.slides.IHyperlink`. |
| [hyperlink_mouse_over](/slides/python-net/aspose.slides/groupshape/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            Read/write :py:class:`aspose.slides.IHyperlink`. |
| [hyperlink_manager](/slides/python-net/aspose.slides/groupshape/hyperlink_manager/) | Returns the hyperlink manager.<br/>            Read-only :py:class:`aspose.slides.IHyperlinkManager`. |
| [hidden](/slides/python-net/aspose.slides/groupshape/hidden/) | Determines whether the shape is hidden.<br/>            Read/write :py:class:`bool`. |
| [z_order_position](/slides/python-net/aspose.slides/groupshape/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Read-only :py:class:`int`. |
| [connection_site_count](/slides/python-net/aspose.slides/groupshape/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            Read-only :py:class:`int`. |
| [rotation](/slides/python-net/aspose.slides/groupshape/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Read/write :py:class:`float`. |
| [x](/slides/python-net/aspose.slides/groupshape/x/) | Returns or sets the x-coordinate of the upper-left corner of the shape.<br/>            Read/write :py:class:`float`. |
| [y](/slides/python-net/aspose.slides/groupshape/y/) | Returns or sets the y-coordinate of the upper-left corner of the shape.<br/>            Read/write :py:class:`float`. |
| [width](/slides/python-net/aspose.slides/groupshape/width/) | Returns or sets the width of the shape.<br/>            Read/write :py:class:`float`. |
| [height](/slides/python-net/aspose.slides/groupshape/height/) | Returns or sets the height of the shape.<br/>            Read/write :py:class:`float`. |
| [black_white_mode](/slides/python-net/aspose.slides/groupshape/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            Read/write :py:enum:`aspose.slides.BlackWhiteMode`. |
| [unique_id](/slides/python-net/aspose.slides/groupshape/unique_id/) | Gets unique shape identifier in presentation scope.<br/>            Read-only :py:class:`int`.<br/>            See also :py:attr:`aspose.slides.Shape.office_interop_shape_id` for getting unique shape identifier in slide scope. |
| [office_interop_shape_id](/slides/python-net/aspose.slides/groupshape/office_interop_shape_id/) | Gets unique shape identifier in slide scope.<br/>            Read-only :py:class:`int`.<br/>            See also :py:attr:`aspose.slides.Shape.unique_id` for getting unique shape identifier in presentation scope. |
| [alternative_text](/slides/python-net/aspose.slides/groupshape/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            Read/write :py:class:`System.String`. |
| [alternative_text_title](/slides/python-net/aspose.slides/groupshape/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            Read/write :py:class:`System.String`. |
| [name](/slides/python-net/aspose.slides/groupshape/name/) | Returns or sets the name of a shape.<br/>            Must be not null. Use empty string value if needed.<br/>            Read/write :py:class:`System.String`. |
| [is_decorative](/slides/python-net/aspose.slides/groupshape/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Reed/write :py:class:`bool`. |
| [shape_lock](/slides/python-net/aspose.slides/groupshape/shape_lock/) | Returns shape's locks.<br/>            Read-only :py:class:`aspose.slides.IGroupShapeLock`. |
| [is_grouped](/slides/python-net/aspose.slides/groupshape/is_grouped/) | Determines whether the shape is grouped.<br/>            Read-only :py:class:`bool`. |
| [parent_group](/slides/python-net/aspose.slides/groupshape/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns null.<br/>            Read-only :py:class:`aspose.slides.IGroupShape`. |
| [slide](/slides/python-net/aspose.slides/groupshape/slide/) | Returns the parent slide of a shape.<br/>            Read-only :py:class:`aspose.slides.IBaseSlide`. |
| [presentation](/slides/python-net/aspose.slides/groupshape/presentation/) | Returns the parent presentation of a slide.<br/>            Read-only :py:class:`aspose.slides.IPresentation`. |
| [group_shape_lock](/slides/python-net/aspose.slides/groupshape/group_shape_lock/) | Returns shape's locks.<br/>            Read-only :py:class:`aspose.slides.IGroupShapeLock`. |
| [shapes](/slides/python-net/aspose.slides/groupshape/shapes/) | Returns the collection of shapes inside the group.<br/>            Read-only :py:class:`aspose.slides.IShapeCollection`. |
| [as_i_shape](/slides/python-net/aspose.slides/groupshape/as_i_shape/) | Allows to get base IShape interface.<br/>            Read-only :py:class:`aspose.slides.IShape`. |
| [as_i_hyperlink_container](/slides/python-net/aspose.slides/groupshape/as_i_hyperlink_container/) |  |
| [as_i_slide_component](/slides/python-net/aspose.slides/groupshape/as_i_slide_component/) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides/groupshape/as_i_presentation_component/) |  |

## Methods

| Method | Description |
| :- | :- |
| [get_thumbnail](/slides/python-net/aspose.slides/groupshape/groupshape/#/) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [get_thumbnail](/slides/python-net/aspose.slides/groupshape/groupshape/#ShapeThumbnailBounds-float-float/) | Returns shape thumbnail. |
| [write_as_svg](/slides/python-net/aspose.slides/groupshape/groupshape/#System.IO.Stream/) | Saves content of Shape as SVG file. |
| [write_as_svg](/slides/python-net/aspose.slides/groupshape/groupshape/#System.IO.Stream-aspose.slides.export.ISVGOptions/) | Saves content of Shape as SVG file. |
| [remove_placeholder](/slides/python-net/aspose.slides/groupshape/groupshape/#/) | Defines that this shape isn't a placeholder. |
| [add_placeholder](/slides/python-net/aspose.slides/groupshape/groupshape/#IPlaceholder/) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [get_base_placeholder](/slides/python-net/aspose.slides/groupshape/groupshape/#/) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from). |

