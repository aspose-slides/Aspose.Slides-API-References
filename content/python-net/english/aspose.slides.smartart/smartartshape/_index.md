---
title: SmartArtShape
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.smartart/smartartshape/
---


SmartArtShape class

Represents SmartArt shape

**Inheritance:**[`SmartArtShape`](/slides/python-net/aspose.slides.smartart/smartartshape)

The SmartArtShape type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [is_text_holder](/slides/python-net/aspose.slides.smartart/smartartshape/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            Read-only .NET type System.Boolean. |
| [placeholder](/slides/python-net/aspose.slides.smartart/smartartshape/placeholder/) | Returns the placeholder for a shape. Returns null if the shape has no placeholder.<br/>            Read-only [`IPlaceholder`](/slides/python-net/aspose.slides/iplaceholder). |
| [custom_data](/slides/python-net/aspose.slides.smartart/smartartshape/custom_data/) | Returns the shape's custom data.<br/>            Read-only [`ICustomData`](/slides/python-net/aspose.slides/icustomdata). |
| [raw_frame](/slides/python-net/aspose.slides.smartart/smartartshape/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            Read/write [`IShapeFrame`](/slides/python-net/aspose.slides/ishapeframe). |
| [frame](/slides/python-net/aspose.slides.smartart/smartartshape/frame/) | Returns or sets the shape frame's properties.<br/>            Read/write [`IShapeFrame`](/slides/python-net/aspose.slides/ishapeframe). |
| [line_format](/slides/python-net/aspose.slides.smartart/smartartshape/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have line properties.<br/>            Read-only [`ILineFormat`](/slides/python-net/aspose.slides/ilineformat). |
| [three_d_format](/slides/python-net/aspose.slides.smartart/smartartshape/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have 3d properties.<br/>            Read-only [`IThreeDFormat`](/slides/python-net/aspose.slides/ithreedformat). |
| [effect_format](/slides/python-net/aspose.slides.smartart/smartartshape/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Note: can return null for certain types of shapes which don't have effect properties.<br/>            Read-only [`IEffectFormat`](/slides/python-net/aspose.slides/ieffectformat). |
| [fill_format](/slides/python-net/aspose.slides.smartart/smartartshape/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have fill properties.<br/>            Read-only [`IFillFormat`](/slides/python-net/aspose.slides/ifillformat). |
| [hyperlink_click](/slides/python-net/aspose.slides.smartart/smartartshape/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            Read/write [`IHyperlink`](/slides/python-net/aspose.slides/ihyperlink). |
| [hyperlink_mouse_over](/slides/python-net/aspose.slides.smartart/smartartshape/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            Read/write [`IHyperlink`](/slides/python-net/aspose.slides/ihyperlink). |
| [hyperlink_manager](/slides/python-net/aspose.slides.smartart/smartartshape/hyperlink_manager/) | Returns the hyperlink manager.<br/>            Read-only [`IHyperlinkManager`](/slides/python-net/aspose.slides/ihyperlinkmanager). |
| [hidden](/slides/python-net/aspose.slides.smartart/smartartshape/hidden/) | Determines whether the shape is hidden.<br/>            Read/write .NET type System.Boolean. |
| [z_order_position](/slides/python-net/aspose.slides.smartart/smartartshape/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Read-only .NET type System.Int32. |
| [connection_site_count](/slides/python-net/aspose.slides.smartart/smartartshape/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            Read-only .NET type System.Int32. |
| [rotation](/slides/python-net/aspose.slides.smartart/smartartshape/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Read/write .NET type System.Single. |
| [x](/slides/python-net/aspose.slides.smartart/smartartshape/x/) | Returns or sets the x-coordinate of the upper-left corner of the shape.<br/>            Read/write .NET type System.Single. |
| [y](/slides/python-net/aspose.slides.smartart/smartartshape/y/) | Returns or sets the y-coordinate of the upper-left corner of the shape.<br/>            Read/write .NET type System.Single. |
| [width](/slides/python-net/aspose.slides.smartart/smartartshape/width/) | Returns or sets the width of the shape.<br/>            Read/write .NET type System.Single. |
| [height](/slides/python-net/aspose.slides.smartart/smartartshape/height/) | Returns or sets the height of the shape.<br/>            Read/write .NET type System.Single. |
| [black_white_mode](/slides/python-net/aspose.slides.smartart/smartartshape/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            Read/write [`BlackWhiteMode`](/slides/python-net/aspose.slides/blackwhitemode). |
| [unique_id](/slides/python-net/aspose.slides.smartart/smartartshape/unique_id/) | Gets unique shape identifier in presentation scope.<br/>            Read-only .NET type System.UInt32.<br/>            See also [`Shape.office_interop_shape_id`](/slides/python-net/aspose.slides/shape#office_interop_shape_id) for getting unique shape identifier in slide scope. |
| [office_interop_shape_id](/slides/python-net/aspose.slides.smartart/smartartshape/office_interop_shape_id/) | Gets unique shape identifier in slide scope.<br/>            Read-only .NET type System.UInt32.<br/>            See also [`Shape.unique_id`](/slides/python-net/aspose.slides/shape#unique_id) for getting unique shape identifier in presentation scope. |
| [alternative_text](/slides/python-net/aspose.slides.smartart/smartartshape/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            Read/write .NET type System.String. |
| [alternative_text_title](/slides/python-net/aspose.slides.smartart/smartartshape/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            Read/write .NET type System.String. |
| [name](/slides/python-net/aspose.slides.smartart/smartartshape/name/) | Returns or sets the name of a shape.<br/>            Must be not null. Use empty string value if needed.<br/>            Read/write .NET type System.String. |
| [is_decorative](/slides/python-net/aspose.slides.smartart/smartartshape/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Reed/write .NET type System.Boolean. |
| [shape_lock](/slides/python-net/aspose.slides.smartart/smartartshape/shape_lock/) | Returns shape's locks.<br/>            Read-only [`IBaseShapeLock`](/slides/python-net/aspose.slides/ibaseshapelock). |
| [is_grouped](/slides/python-net/aspose.slides.smartart/smartartshape/is_grouped/) | Determines whether the shape is grouped.<br/>            Read-only .NET type System.Boolean. |
| [parent_group](/slides/python-net/aspose.slides.smartart/smartartshape/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns null.<br/>            Read-only [`IGroupShape`](/slides/python-net/aspose.slides/igroupshape). |
| [slide](/slides/python-net/aspose.slides.smartart/smartartshape/slide/) | Returns the parent slide of a shape.<br/>            Read-only [`IBaseSlide`](/slides/python-net/aspose.slides/ibaseslide). |
| [presentation](/slides/python-net/aspose.slides.smartart/smartartshape/presentation/) | Returns the parent presentation of a slide.<br/>            Read-only [`IPresentation`](/slides/python-net/aspose.slides/ipresentation). |
| [shape_style](/slides/python-net/aspose.slides.smartart/smartartshape/shape_style/) | Returns shape's style object.<br/>            Read-only [`IShapeStyle`](/slides/python-net/aspose.slides/ishapestyle). |
| [shape_type](/slides/python-net/aspose.slides.smartart/smartartshape/shape_type/) | Returns or sets the geometry preset type.<br/>            Note: on value changing all adjustment values will reset to their default values.<br/>            Read/write [`ShapeType`](/slides/python-net/aspose.slides/shapetype). |
| [adjustments](/slides/python-net/aspose.slides.smartart/smartartshape/adjustments/) | Returns a collection of shape's adjustment values.<br/>            Read-only [`IAdjustValueCollection`](/slides/python-net/aspose.slides/iadjustvaluecollection). |
| [text_frame](/slides/python-net/aspose.slides.smartart/smartartshape/text_frame/) | Returns text of the SmartArt shape.<br/>            Read-only [`ITextFrame`](/slides/python-net/aspose.slides/itextframe). |
| [as_i_hyperlink_container](/slides/python-net/aspose.slides.smartart/smartartshape/as_i_hyperlink_container/) |  |
| [as_i_slide_component](/slides/python-net/aspose.slides.smartart/smartartshape/as_i_slide_component/) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides.smartart/smartartshape/as_i_presentation_component/) |  |
| [as_i_shape](/slides/python-net/aspose.slides.smartart/smartartshape/as_i_shape/) |  |
| [as_i_geometry_shape](/slides/python-net/aspose.slides.smartart/smartartshape/as_i_geometry_shape/) |  |

## Methods

| Method | Description |
| :- | :- |
| [get_thumbnail](/slides/python-net/aspose.slides.smartart/smartartshape/get_thumbnail/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [get_thumbnail](/slides/python-net/aspose.slides.smartart/smartartshape/get_thumbnail/#ShapeThumbnailBounds-float-float) |  |
| [write_as_svg](/slides/python-net/aspose.slides.smartart/smartartshape/write_as_svg/#System.IO.Stream) | Saves content of Shape as SVG file. |
| [write_as_svg](/slides/python-net/aspose.slides.smartart/smartartshape/write_as_svg/#System.IO.Stream-aspose.slides.export.ISVGOptions) | Saves content of Shape as SVG file. |
| [remove_placeholder](/slides/python-net/aspose.slides.smartart/smartartshape/remove_placeholder/#) | Defines that this shape isn't a placeholder. |
| [add_placeholder](/slides/python-net/aspose.slides.smartart/smartartshape/add_placeholder/#IPlaceholder) |  |
| [get_base_placeholder](/slides/python-net/aspose.slides.smartart/smartartshape/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            A null is returned if the current shape is not inherited. |
| [get_geometry_paths](/slides/python-net/aspose.slides.smartart/smartartshape/get_geometry_paths/#) | Returns the copy of path of the geometry shape. Coordinates are relative to the left top corner of the shape. |
| [set_geometry_path](/slides/python-net/aspose.slides.smartart/smartartshape/set_geometry_path/#IGeometryPath) |  |
| [set_geometry_paths](/slides/python-net/aspose.slides.smartart/smartartshape/set_geometry_paths/#List[IGeometryPath]) |  |
| [create_shape_elements](/slides/python-net/aspose.slides.smartart/smartartshape/create_shape_elements/#) | Creates and returns array of shape's elements. |

