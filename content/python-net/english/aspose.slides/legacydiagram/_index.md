---
title: LegacyDiagram
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/legacydiagram/
---


LegacyDiagram class

Represents a legacy diagram object.

**Inheritance:**[`LegacyDiagram`](/slides/python-net/aspose.slides/legacydiagram) → [`GraphicalObject`](/slides/python-net/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/aspose.slides/shape)

The LegacyDiagram type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [is_text_holder](/slides/python-net/aspose.slides/legacydiagram/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            Read-only <br/>.NET type System.Boolean<br/>. |
| [placeholder](/slides/python-net/aspose.slides/legacydiagram/placeholder/) | Returns the placeholder for a shape. Returns null if the shape has no placeholder.<br/>            Read-only <br/>[`IPlaceholder`](/slides/python-net/aspose.slides/iplaceholder)<br/>. |
| [custom_data](/slides/python-net/aspose.slides/legacydiagram/custom_data/) | Returns the shape's custom data.<br/>            Read-only <br/>[`ICustomData`](/slides/python-net/aspose.slides/icustomdata)<br/>. |
| [raw_frame](/slides/python-net/aspose.slides/legacydiagram/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            Read/write <br/>[`IShapeFrame`](/slides/python-net/aspose.slides/ishapeframe)<br/>. |
| [frame](/slides/python-net/aspose.slides/legacydiagram/frame/) | Returns or sets the shape frame's properties.<br/>            Read/write <br/>[`IShapeFrame`](/slides/python-net/aspose.slides/ishapeframe)<br/>. |
| [line_format](/slides/python-net/aspose.slides/legacydiagram/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have line properties.<br/>            Read-only <br/>[`ILineFormat`](/slides/python-net/aspose.slides/ilineformat)<br/>. |
| [three_d_format](/slides/python-net/aspose.slides/legacydiagram/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have 3d properties.<br/>            Read-only <br/>[`IThreeDFormat`](/slides/python-net/aspose.slides/ithreedformat)<br/>. |
| [effect_format](/slides/python-net/aspose.slides/legacydiagram/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Note: can return null for certain types of shapes which don't have effect properties.<br/>            Read-only <br/>[`IEffectFormat`](/slides/python-net/aspose.slides/ieffectformat)<br/>. |
| [fill_format](/slides/python-net/aspose.slides/legacydiagram/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have fill properties.<br/>            Read-only <br/>[`IFillFormat`](/slides/python-net/aspose.slides/ifillformat)<br/>. |
| [hyperlink_click](/slides/python-net/aspose.slides/legacydiagram/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            Read/write <br/>[`IHyperlink`](/slides/python-net/aspose.slides/ihyperlink)<br/>. |
| [hyperlink_mouse_over](/slides/python-net/aspose.slides/legacydiagram/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            Read/write <br/>[`IHyperlink`](/slides/python-net/aspose.slides/ihyperlink)<br/>. |
| [hyperlink_manager](/slides/python-net/aspose.slides/legacydiagram/hyperlink_manager/) | Returns the hyperlink manager.<br/>            Read-only <br/>[`IHyperlinkManager`](/slides/python-net/aspose.slides/ihyperlinkmanager)<br/>. |
| [hidden](/slides/python-net/aspose.slides/legacydiagram/hidden/) | Determines whether the shape is hidden.<br/>            Read/write <br/>.NET type System.Boolean<br/>. |
| [z_order_position](/slides/python-net/aspose.slides/legacydiagram/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Read-only <br/>.NET type System.Int32<br/>. |
| [connection_site_count](/slides/python-net/aspose.slides/legacydiagram/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            Read-only <br/>.NET type System.Int32<br/>. |
| [rotation](/slides/python-net/aspose.slides/legacydiagram/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Read/write <br/>.NET type System.Single<br/>. |
| [x](/slides/python-net/aspose.slides/legacydiagram/x/) | Returns or sets the x-coordinate of the upper-left corner of the shape.<br/>            Read/write <br/>.NET type System.Single<br/>. |
| [y](/slides/python-net/aspose.slides/legacydiagram/y/) | Returns or sets the y-coordinate of the upper-left corner of the shape.<br/>            Read/write <br/>.NET type System.Single<br/>. |
| [width](/slides/python-net/aspose.slides/legacydiagram/width/) | Returns or sets the width of the shape.<br/>            Read/write <br/>.NET type System.Single<br/>. |
| [height](/slides/python-net/aspose.slides/legacydiagram/height/) | Returns or sets the height of the shape.<br/>            Read/write <br/>.NET type System.Single<br/>. |
| [black_white_mode](/slides/python-net/aspose.slides/legacydiagram/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            Read/write <br/>[`BlackWhiteMode`](/slides/python-net/aspose.slides/blackwhitemode)<br/>. |
| [unique_id](/slides/python-net/aspose.slides/legacydiagram/unique_id/) | Gets unique shape identifier in presentation scope.<br/>            Read-only <br/>.NET type System.UInt32<br/>.<br/>            See also <br/>[`Shape.office_interop_shape_id`](/slides/python-net/aspose.slides/shape#office_interop_shape_id)<br/> for getting unique shape identifier in slide scope. |
| [office_interop_shape_id](/slides/python-net/aspose.slides/legacydiagram/office_interop_shape_id/) | Gets unique shape identifier in slide scope.<br/>            Read-only <br/>.NET type System.UInt32<br/>.<br/>            See also <br/>[`Shape.unique_id`](/slides/python-net/aspose.slides/shape#unique_id)<br/> for getting unique shape identifier in presentation scope. |
| [alternative_text](/slides/python-net/aspose.slides/legacydiagram/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            Read/write <br/>.NET type System.String<br/>. |
| [alternative_text_title](/slides/python-net/aspose.slides/legacydiagram/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            Read/write <br/>.NET type System.String<br/>. |
| [name](/slides/python-net/aspose.slides/legacydiagram/name/) | Returns or sets the name of a shape.<br/>            Must be not null. Use empty string value if needed.<br/>            Read/write <br/>.NET type System.String<br/>. |
| [is_decorative](/slides/python-net/aspose.slides/legacydiagram/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Reed/write <br/>.NET type System.Boolean<br/>. |
| [shape_lock](/slides/python-net/aspose.slides/legacydiagram/shape_lock/) | Returns shape's locks.<br/>            Read-only <br/>[`IGraphicalObjectLock`](/slides/python-net/aspose.slides/igraphicalobjectlock)<br/>. |
| [is_grouped](/slides/python-net/aspose.slides/legacydiagram/is_grouped/) | Determines whether the shape is grouped.<br/>            Read-only <br/>.NET type System.Boolean<br/>. |
| [parent_group](/slides/python-net/aspose.slides/legacydiagram/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns null.<br/>            Read-only <br/>[`IGroupShape`](/slides/python-net/aspose.slides/igroupshape)<br/>. |
| [slide](/slides/python-net/aspose.slides/legacydiagram/slide/) | Returns the parent slide of a shape.<br/>            Read-only <br/>[`IBaseSlide`](/slides/python-net/aspose.slides/ibaseslide)<br/>. |
| [presentation](/slides/python-net/aspose.slides/legacydiagram/presentation/) | Returns the parent presentation of a slide.<br/>            Read-only <br/>[`IPresentation`](/slides/python-net/aspose.slides/ipresentation)<br/>. |
| [graphical_object_lock](/slides/python-net/aspose.slides/legacydiagram/graphical_object_lock/) | Returns shape's locks.<br/>            Read-only <br/>[`IGraphicalObjectLock`](/slides/python-net/aspose.slides/igraphicalobjectlock)<br/>. |
| [as_i_graphical_object](/slides/python-net/aspose.slides/legacydiagram/as_i_graphical_object/) | Allows to get base IGraphicalObject interface.<br/>            Read-only <br/>[`IGraphicalObject`](/slides/python-net/aspose.slides/igraphicalobject)<br/>. |
| [as_i_hyperlink_container](/slides/python-net/aspose.slides/legacydiagram/as_i_hyperlink_container/) |  |
| [as_i_slide_component](/slides/python-net/aspose.slides/legacydiagram/as_i_slide_component/) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides/legacydiagram/as_i_presentation_component/) |  |
| [as_i_shape](/slides/python-net/aspose.slides/legacydiagram/as_i_shape/) |  |

## Methods

| Method | Description |
| :- | :- |
| [get_thumbnail](/slides/python-net/aspose.slides/legacydiagram/legacydiagram/#/) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [get_thumbnail](/slides/python-net/aspose.slides/legacydiagram/legacydiagram/#ShapeThumbnailBounds-float-float/) | Returns shape thumbnail. |
| [write_as_svg](/slides/python-net/aspose.slides/legacydiagram/legacydiagram/#System.IO.Stream/) | Saves content of Shape as SVG file. |
| [write_as_svg](/slides/python-net/aspose.slides/legacydiagram/legacydiagram/#System.IO.Stream-aspose.slides.export.ISVGOptions/) | Saves content of Shape as SVG file. |
| [remove_placeholder](/slides/python-net/aspose.slides/legacydiagram/legacydiagram/#/) | Defines that this shape isn't a placeholder. |
| [add_placeholder](/slides/python-net/aspose.slides/legacydiagram/legacydiagram/#IPlaceholder/) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [get_base_placeholder](/slides/python-net/aspose.slides/legacydiagram/legacydiagram/#/) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            <br/>A null is returned if the current shape is not inherited. |
| [convert_to_smart_art](/slides/python-net/aspose.slides/legacydiagram/legacydiagram/#/) | Converts legacy digram to editable SmartArt object. <br/>            Created SmartArt object adds to parent group shape at the same position. |
| [convert_to_group_shape](/slides/python-net/aspose.slides/legacydiagram/legacydiagram/#/) | Converts legacy digram to editable group shape. <br/>            Created GroupShape object adds to parent group shape at the same position. |

