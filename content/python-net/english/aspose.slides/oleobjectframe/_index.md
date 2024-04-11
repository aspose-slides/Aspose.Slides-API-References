---
title: OleObjectFrame
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/oleobjectframe/
---


OleObjectFrame class

Represents an OLE object on a slide.

**Inheritance:**[`OleObjectFrame`](/slides/python-net/aspose.slides/oleobjectframe) → [`GraphicalObject`](/slides/python-net/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/aspose.slides/shape)

The OleObjectFrame type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [is_text_holder](/slides/python-net/aspose.slides/oleobjectframe/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            Read-only <br/>.NET type System.Boolean<br/>. |
| [placeholder](/slides/python-net/aspose.slides/oleobjectframe/placeholder/) | Returns the placeholder for a shape. Returns null if the shape has no placeholder.<br/>            Read-only <br/>[`IPlaceholder`](/slides/python-net/aspose.slides/iplaceholder)<br/>. |
| [custom_data](/slides/python-net/aspose.slides/oleobjectframe/custom_data/) | Returns the shape's custom data.<br/>            Read-only <br/>[`ICustomData`](/slides/python-net/aspose.slides/icustomdata)<br/>. |
| [raw_frame](/slides/python-net/aspose.slides/oleobjectframe/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            Read/write <br/>[`IShapeFrame`](/slides/python-net/aspose.slides/ishapeframe)<br/>. |
| [frame](/slides/python-net/aspose.slides/oleobjectframe/frame/) | Returns or sets the shape frame's properties.<br/>            Read/write <br/>[`IShapeFrame`](/slides/python-net/aspose.slides/ishapeframe)<br/>. |
| [line_format](/slides/python-net/aspose.slides/oleobjectframe/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have line properties.<br/>            Read-only <br/>[`ILineFormat`](/slides/python-net/aspose.slides/ilineformat)<br/>. |
| [three_d_format](/slides/python-net/aspose.slides/oleobjectframe/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have 3d properties.<br/>            Read-only <br/>[`IThreeDFormat`](/slides/python-net/aspose.slides/ithreedformat)<br/>. |
| [effect_format](/slides/python-net/aspose.slides/oleobjectframe/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Note: can return null for certain types of shapes which don't have effect properties.<br/>            Read-only <br/>[`IEffectFormat`](/slides/python-net/aspose.slides/ieffectformat)<br/>. |
| [fill_format](/slides/python-net/aspose.slides/oleobjectframe/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have fill properties.<br/>            Read-only <br/>[`IFillFormat`](/slides/python-net/aspose.slides/ifillformat)<br/>. |
| [hyperlink_click](/slides/python-net/aspose.slides/oleobjectframe/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            Read/write <br/>[`IHyperlink`](/slides/python-net/aspose.slides/ihyperlink)<br/>. |
| [hyperlink_mouse_over](/slides/python-net/aspose.slides/oleobjectframe/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            Read/write <br/>[`IHyperlink`](/slides/python-net/aspose.slides/ihyperlink)<br/>. |
| [hyperlink_manager](/slides/python-net/aspose.slides/oleobjectframe/hyperlink_manager/) | Returns the hyperlink manager.<br/>            Read-only <br/>[`IHyperlinkManager`](/slides/python-net/aspose.slides/ihyperlinkmanager)<br/>. |
| [hidden](/slides/python-net/aspose.slides/oleobjectframe/hidden/) | Determines whether the shape is hidden.<br/>            Read/write <br/>.NET type System.Boolean<br/>. |
| [z_order_position](/slides/python-net/aspose.slides/oleobjectframe/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Read-only <br/>.NET type System.Int32<br/>. |
| [connection_site_count](/slides/python-net/aspose.slides/oleobjectframe/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            Read-only <br/>.NET type System.Int32<br/>. |
| [rotation](/slides/python-net/aspose.slides/oleobjectframe/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Read/write <br/>.NET type System.Single<br/>. |
| [x](/slides/python-net/aspose.slides/oleobjectframe/x/) | Returns or sets the x-coordinate of the upper-left corner of the shape.<br/>            Read/write <br/>.NET type System.Single<br/>. |
| [y](/slides/python-net/aspose.slides/oleobjectframe/y/) | Returns or sets the y-coordinate of the upper-left corner of the shape.<br/>            Read/write <br/>.NET type System.Single<br/>. |
| [width](/slides/python-net/aspose.slides/oleobjectframe/width/) | Returns or sets the width of the shape.<br/>            Read/write <br/>.NET type System.Single<br/>. |
| [height](/slides/python-net/aspose.slides/oleobjectframe/height/) | Returns or sets the height of the shape.<br/>            Read/write <br/>.NET type System.Single<br/>. |
| [black_white_mode](/slides/python-net/aspose.slides/oleobjectframe/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            Read/write <br/>[`BlackWhiteMode`](/slides/python-net/aspose.slides/blackwhitemode)<br/>. |
| [unique_id](/slides/python-net/aspose.slides/oleobjectframe/unique_id/) | Gets unique shape identifier in presentation scope.<br/>            Read-only <br/>.NET type System.UInt32<br/>.<br/>            See also <br/>[`Shape.office_interop_shape_id`](/slides/python-net/aspose.slides/shape#office_interop_shape_id)<br/> for getting unique shape identifier in slide scope. |
| [office_interop_shape_id](/slides/python-net/aspose.slides/oleobjectframe/office_interop_shape_id/) | Gets unique shape identifier in slide scope.<br/>            Read-only <br/>.NET type System.UInt32<br/>.<br/>            See also <br/>[`Shape.unique_id`](/slides/python-net/aspose.slides/shape#unique_id)<br/> for getting unique shape identifier in presentation scope. |
| [alternative_text](/slides/python-net/aspose.slides/oleobjectframe/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            Read/write <br/>.NET type System.String<br/>. |
| [alternative_text_title](/slides/python-net/aspose.slides/oleobjectframe/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            Read/write <br/>.NET type System.String<br/>. |
| [name](/slides/python-net/aspose.slides/oleobjectframe/name/) | Returns or sets the name of a shape.<br/>            Must be not null. Use empty string value if needed.<br/>            Read/write <br/>.NET type System.String<br/>. |
| [is_decorative](/slides/python-net/aspose.slides/oleobjectframe/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Reed/write <br/>.NET type System.Boolean<br/>. |
| [shape_lock](/slides/python-net/aspose.slides/oleobjectframe/shape_lock/) | Returns shape's locks.<br/>            Read-only <br/>[`IGraphicalObjectLock`](/slides/python-net/aspose.slides/igraphicalobjectlock)<br/>. |
| [is_grouped](/slides/python-net/aspose.slides/oleobjectframe/is_grouped/) | Determines whether the shape is grouped.<br/>            Read-only <br/>.NET type System.Boolean<br/>. |
| [parent_group](/slides/python-net/aspose.slides/oleobjectframe/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns null.<br/>            Read-only <br/>[`IGroupShape`](/slides/python-net/aspose.slides/igroupshape)<br/>. |
| [slide](/slides/python-net/aspose.slides/oleobjectframe/slide/) | Returns the parent slide of a shape.<br/>            Read-only <br/>[`IBaseSlide`](/slides/python-net/aspose.slides/ibaseslide)<br/>. |
| [presentation](/slides/python-net/aspose.slides/oleobjectframe/presentation/) | Returns the parent presentation of a slide.<br/>            Read-only <br/>[`IPresentation`](/slides/python-net/aspose.slides/ipresentation)<br/>. |
| [graphical_object_lock](/slides/python-net/aspose.slides/oleobjectframe/graphical_object_lock/) | Returns shape's locks.<br/>            Read-only <br/>[`IGraphicalObjectLock`](/slides/python-net/aspose.slides/igraphicalobjectlock)<br/>. |
| [substitute_picture_format](/slides/python-net/aspose.slides/oleobjectframe/substitute_picture_format/) | Returns OleObject image fill properties object.<br/>            Read-only <br/>[`IPictureFillFormat`](/slides/python-net/aspose.slides/ipicturefillformat)<br/>. |
| [substitute_picture_title](/slides/python-net/aspose.slides/oleobjectframe/substitute_picture_title/) | Returns or sets the title for OleObject icon.<br/>            Read/write <br/>.NET type System.String<br/>. |
| [object_name](/slides/python-net/aspose.slides/oleobjectframe/object_name/) | Returns or sets the name of an object.<br/>            Read/write <br/>.NET type System.String<br/>. |
| [object_prog_id](/slides/python-net/aspose.slides/oleobjectframe/object_prog_id/) | Returns the ProgID of an object.<br/>            Read only <br/>.NET type System.String<br/>. |
| [link_file_name](/slides/python-net/aspose.slides/oleobjectframe/link_file_name/) | Returns the full path to a linked file. Short file name will be used.<br/>            Read-only <br/>.NET type System.String<br/>. |
| [link_path_long](/slides/python-net/aspose.slides/oleobjectframe/link_path_long/) | Returns the full path to a linked file. Long file name will be used.<br/>            Read/write <br/>.NET type System.String<br/>. |
| [link_path_relative](/slides/python-net/aspose.slides/oleobjectframe/link_path_relative/) | Returns the relative path to a linked file if present, otherwise returns an empty string.<br/>             Readonly <br/>.NET type System.String<br/>. |
| [embedded_file_label](/slides/python-net/aspose.slides/oleobjectframe/embedded_file_label/) | Returns the file name of embedded OLE object |
| [embedded_file_name](/slides/python-net/aspose.slides/oleobjectframe/embedded_file_name/) | Returns the path of embedded OLE object |
| [embedded_data](/slides/python-net/aspose.slides/oleobjectframe/embedded_data/) | Gets or sets information about OLE embedded data.<br/>            Read/write <br/>[`IOleEmbeddedDataInfo`](/slides/python-net/aspose.slides/ioleembeddeddatainfo)<br/>. |
| [is_object_icon](/slides/python-net/aspose.slides/oleobjectframe/is_object_icon/) | Determines whether an object is visible as icon.<br/>            Read/write <br/>.NET type System.Boolean<br/>. |
| [is_object_link](/slides/python-net/aspose.slides/oleobjectframe/is_object_link/) | Determines whether an object is linked to external file.<br/>            Read-only <br/>.NET type System.Boolean<br/>. |
| [as_i_graphical_object](/slides/python-net/aspose.slides/oleobjectframe/as_i_graphical_object/) | Allows to get base IGraphicalObject interface.<br/>            Read-only <br/>[`IGraphicalObject`](/slides/python-net/aspose.slides/igraphicalobject)<br/>. |
| [update_automatic](/slides/python-net/aspose.slides/oleobjectframe/update_automatic/) | Determines if the linked embedded object is automatically updated when the presentation is opened or printed.<br/>            Read/write <br/>.NET type System.Boolean<br/>. |
| [as_i_hyperlink_container](/slides/python-net/aspose.slides/oleobjectframe/as_i_hyperlink_container/) |  |
| [as_i_slide_component](/slides/python-net/aspose.slides/oleobjectframe/as_i_slide_component/) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides/oleobjectframe/as_i_presentation_component/) |  |
| [as_i_shape](/slides/python-net/aspose.slides/oleobjectframe/as_i_shape/) |  |

## Methods

| Method | Description |
| :- | :- |
| [get_thumbnail](/slides/python-net/aspose.slides/oleobjectframe/oleobjectframe/#/) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [get_thumbnail](/slides/python-net/aspose.slides/oleobjectframe/oleobjectframe/#ShapeThumbnailBounds-float-float/) | Returns shape thumbnail. |
| [write_as_svg](/slides/python-net/aspose.slides/oleobjectframe/oleobjectframe/#System.IO.Stream/) | Saves content of Shape as SVG file. |
| [write_as_svg](/slides/python-net/aspose.slides/oleobjectframe/oleobjectframe/#System.IO.Stream-aspose.slides.export.ISVGOptions/) | Saves content of Shape as SVG file. |
| [remove_placeholder](/slides/python-net/aspose.slides/oleobjectframe/oleobjectframe/#/) | Defines that this shape isn't a placeholder. |
| [add_placeholder](/slides/python-net/aspose.slides/oleobjectframe/oleobjectframe/#IPlaceholder/) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [get_base_placeholder](/slides/python-net/aspose.slides/oleobjectframe/oleobjectframe/#/) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            <br/>A null is returned if the current shape is not inherited. |
| [set_embedded_data](/slides/python-net/aspose.slides/oleobjectframe/oleobjectframe/#IOleEmbeddedDataInfo/) | Sets information about OLE embedded data.<br/>            <br/><br/>            This method changes the properties of the object to reflect the new data and <br/>            sets the IsObjectLink flag to false, indicating that the OLE object is embedded. |

