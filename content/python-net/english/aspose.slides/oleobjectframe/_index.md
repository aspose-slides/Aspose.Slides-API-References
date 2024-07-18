---
title: OleObjectFrame class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/oleobjectframe/
---


## OleObjectFrame class

Represents an OLE object on a slide.

**Inheritance:**[`OleObjectFrame`](/slides/python-net/aspose.slides/oleobjectframe) → [`GraphicalObject`](/slides/python-net/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/aspose.slides/shape)

The OleObjectFrame type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/aspose.slides/oleobjectframe/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            Read-only **bool**. |
| [`placeholder`](/slides/python-net/aspose.slides/oleobjectframe/placeholder/) | Returns the placeholder for a shape. Returns null if the shape has no placeholder.<br/>            Read-only [`IPlaceholder`](/slides/python-net/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/aspose.slides/oleobjectframe/custom_data/) | Returns the shape's custom data.<br/>            Read-only [`ICustomData`](/slides/python-net/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/aspose.slides/oleobjectframe/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            Read/write [`IShapeFrame`](/slides/python-net/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/aspose.slides/oleobjectframe/frame/) | Returns or sets the shape frame's properties.<br/>            Read/write [`IShapeFrame`](/slides/python-net/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/aspose.slides/oleobjectframe/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have line properties.<br/>            Read-only [`ILineFormat`](/slides/python-net/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/aspose.slides/oleobjectframe/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have 3d properties.<br/>            Read-only [`IThreeDFormat`](/slides/python-net/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/aspose.slides/oleobjectframe/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Note: can return null for certain types of shapes which don't have effect properties.<br/>            Read-only [`IEffectFormat`](/slides/python-net/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/aspose.slides/oleobjectframe/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Note: can return null for certain types of shapes which don't have fill properties.<br/>            Read-only [`IFillFormat`](/slides/python-net/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/aspose.slides/oleobjectframe/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            Read/write [`IHyperlink`](/slides/python-net/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/aspose.slides/oleobjectframe/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            Read/write [`IHyperlink`](/slides/python-net/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/aspose.slides/oleobjectframe/hyperlink_manager/) | Returns the hyperlink manager.<br/>            Read-only [`IHyperlinkManager`](/slides/python-net/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/aspose.slides/oleobjectframe/hidden/) | Determines whether the shape is hidden.<br/>            Read/write **bool**. |
| [`z_order_position`](/slides/python-net/aspose.slides/oleobjectframe/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Read-only **int**. |
| [`connection_site_count`](/slides/python-net/aspose.slides/oleobjectframe/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            Read-only **int**. |
| [`rotation`](/slides/python-net/aspose.slides/oleobjectframe/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Read/write **float**. |
| [`x`](/slides/python-net/aspose.slides/oleobjectframe/x/) | Returns or sets the x-coordinate of the upper-left corner of the shape.<br/>            Read/write **float**. |
| [`y`](/slides/python-net/aspose.slides/oleobjectframe/y/) | Returns or sets the y-coordinate of the upper-left corner of the shape.<br/>            Read/write **float**. |
| [`width`](/slides/python-net/aspose.slides/oleobjectframe/width/) | Returns or sets the width of the shape.<br/>            Read/write **float**. |
| [`height`](/slides/python-net/aspose.slides/oleobjectframe/height/) | Returns or sets the height of the shape.<br/>            Read/write **float**. |
| [`black_white_mode`](/slides/python-net/aspose.slides/oleobjectframe/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            Read/write [`BlackWhiteMode`](/slides/python-net/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/aspose.slides/oleobjectframe/unique_id/) | Gets unique shape identifier in presentation scope.<br/>            Read-only **int**.<br/>            See also [`Shape.office_interop_shape_id`](/slides/python-net/aspose.slides/shape/office_interop_shape_id) for getting unique shape identifier in slide scope. |
| [`office_interop_shape_id`](/slides/python-net/aspose.slides/oleobjectframe/office_interop_shape_id/) | Gets unique shape identifier in slide scope.<br/>            Read-only **int**.<br/>            See also [`Shape.unique_id`](/slides/python-net/aspose.slides/shape/unique_id) for getting unique shape identifier in presentation scope. |
| [`alternative_text`](/slides/python-net/aspose.slides/oleobjectframe/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            Read/write **str**. |
| [`alternative_text_title`](/slides/python-net/aspose.slides/oleobjectframe/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            Read/write **str**. |
| [`name`](/slides/python-net/aspose.slides/oleobjectframe/name/) | Returns or sets the name of a shape.<br/>            Must be not null. Use empty string value if needed.<br/>            Read/write **str**. |
| [`is_decorative`](/slides/python-net/aspose.slides/oleobjectframe/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/aspose.slides/oleobjectframe/shape_lock/) | Returns shape's locks.<br/>            Read-only [`IGraphicalObjectLock`](/slides/python-net/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/aspose.slides/oleobjectframe/is_grouped/) | Determines whether the shape is grouped.<br/>            Read-only **bool**. |
| [`parent_group`](/slides/python-net/aspose.slides/oleobjectframe/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns null.<br/>            Read-only [`IGroupShape`](/slides/python-net/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/aspose.slides/oleobjectframe/slide/) | Returns the parent slide of a shape.<br/>            Read-only [`IBaseSlide`](/slides/python-net/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/aspose.slides/oleobjectframe/presentation/) | Returns the parent presentation of a slide.<br/>            Read-only [`IPresentation`](/slides/python-net/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/aspose.slides/oleobjectframe/graphical_object_lock/) | Returns shape's locks.<br/>            Read-only [`IGraphicalObjectLock`](/slides/python-net/aspose.slides/igraphicalobjectlock). |
| [`substitute_picture_format`](/slides/python-net/aspose.slides/oleobjectframe/substitute_picture_format/) | Returns OleObject image fill properties object.<br/>            Read-only [`IPictureFillFormat`](/slides/python-net/aspose.slides/ipicturefillformat). |
| [`substitute_picture_title`](/slides/python-net/aspose.slides/oleobjectframe/substitute_picture_title/) | Returns or sets the title for OleObject icon.<br/>            Read/write **str**. |
| [`object_name`](/slides/python-net/aspose.slides/oleobjectframe/object_name/) | Returns or sets the name of an object.<br/>            Read/write **str**. |
| [`object_prog_id`](/slides/python-net/aspose.slides/oleobjectframe/object_prog_id/) | Returns the ProgID of an object.<br/>            Read only **str**. |
| [`link_file_name`](/slides/python-net/aspose.slides/oleobjectframe/link_file_name/) | Returns the full path to a linked file. Short file name will be used.<br/>            Read-only **str**. |
| [`link_path_long`](/slides/python-net/aspose.slides/oleobjectframe/link_path_long/) | Returns the full path to a linked file. Long file name will be used.<br/>            Read/write **str**. |
| [`link_path_relative`](/slides/python-net/aspose.slides/oleobjectframe/link_path_relative/) | Returns the relative path to a linked file if present, otherwise returns an empty string.<br/>             Readonly **str**. |
| [`embedded_file_label`](/slides/python-net/aspose.slides/oleobjectframe/embedded_file_label/) | Returns the file name of embedded OLE object |
| [`embedded_file_name`](/slides/python-net/aspose.slides/oleobjectframe/embedded_file_name/) | Returns the path of embedded OLE object |
| [`embedded_data`](/slides/python-net/aspose.slides/oleobjectframe/embedded_data/) | Gets or sets information about OLE embedded data.<br/>            Read/write [`IOleEmbeddedDataInfo`](/slides/python-net/aspose.slides/ioleembeddeddatainfo). |
| [`is_object_icon`](/slides/python-net/aspose.slides/oleobjectframe/is_object_icon/) | Determines whether an object is visible as icon.<br/>            Read/write **bool**. |
| [`is_object_link`](/slides/python-net/aspose.slides/oleobjectframe/is_object_link/) | Determines whether an object is linked to external file.<br/>            Read-only **bool**. |
| [`update_automatic`](/slides/python-net/aspose.slides/oleobjectframe/update_automatic/) | Determines if the linked embedded object is automatically updated when the presentation is opened or printed.<br/>            Read/write **bool**. |

## Methods

| Method | Description |
| :- | :- |
| [`get_thumbnail`](/slides/python-net/aspose.slides/oleobjectframe/get_thumbnail/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_thumbnail`](/slides/python-net/aspose.slides/oleobjectframe/get_thumbnail/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [`get_image`](/slides/python-net/aspose.slides/oleobjectframe/get_image/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image`](/slides/python-net/aspose.slides/oleobjectframe/get_image/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [`write_as_svg`](/slides/python-net/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase) | Saves content of Shape as SVG file. |
| [`write_as_svg`](/slides/python-net/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file. |
| [`remove_placeholder`](/slides/python-net/aspose.slides/oleobjectframe/remove_placeholder/#) | Defines that this shape isn't a placeholder. |
| [`add_placeholder`](/slides/python-net/aspose.slides/oleobjectframe/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [`get_base_placeholder`](/slides/python-net/aspose.slides/oleobjectframe/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>A null is returned if the current shape is not inherited. |
| [`set_embedded_data`](/slides/python-net/aspose.slides/oleobjectframe/set_embedded_data/#ioleembeddeddatainfo) | Sets information about OLE embedded data.<br/><br/>This method changes the properties of the object to reflect the new data and <br/>            sets the IsObjectLink flag to false, indicating that the OLE object is embedded. |


### See Also
* class [`GraphicalObject`](/slides/python-net/aspose.slides/graphicalobject)
* class [`OleObjectFrame`](/slides/python-net/aspose.slides/oleobjectframe)
* class [`Shape`](/slides/python-net/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

