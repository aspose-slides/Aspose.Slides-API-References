---
title: SummaryZoomSection class
second_title: Aspose.Slides 用於 Python 的 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection 類別

Represents a Summary Zoom Section object in a Summary Zoom frame.

**Inheritance:**[`SummaryZoomSection`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection) → [`SectionZoomFrame`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe) → [`ZoomObject`](/slides/python-net/zh-hant/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/zh-hant/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)

The SummaryZoomSection type exposes the following members:

## 屬性

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            Read-only **bool**. |
| [`placeholder`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/placeholder/) | Returns the placeholder for a shape. Returns None if the shape has no placeholder.<br/>            Read-only [`IPlaceholder`](/slides/python-net/zh-hant/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/custom_data/) | Returns the shape's custom data.<br/>            Read-only [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            Read/write [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/frame/) | Returns or sets the shape frame's properties.<br/>            Read/write [`IShapeFrame`](/slides/python-net/zh-hant/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have line properties.<br/>            Read-only [`ILineFormat`](/slides/python-net/zh-hant/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have 3d properties.<br/>            Read-only [`IThreeDFormat`](/slides/python-net/zh-hant/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Note: can return None for certain types of shapes which don't have effect properties.<br/>            Read-only [`IEffectFormat`](/slides/python-net/zh-hant/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have fill properties.<br/>            Read-only [`IFillFormat`](/slides/python-net/zh-hant/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            Read/write [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            Read/write [`IHyperlink`](/slides/python-net/zh-hant/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/hyperlink_manager/) | Returns the hyperlink manager.<br/>            Read-only [`IHyperlinkManager`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/hidden/) | Determines whether the shape is hidden.<br/>            Read/write **bool**. |
| [`z_order_position`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Read-only **int**. |
| [`connection_site_count`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            Read-only **int**. |
| [`rotation`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Read/write **float**. |
| [`x`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/x/) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points.<br/>            Read/write **float**. |
| [`y`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/y/) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points.<br/>            Read/write **float**. |
| [`width`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/width/) | Gets or sets the width of the shape, measured in points.<br/>            Read/write **float**. |
| [`height`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/height/) | Gets or sets the height of the shape, measured in points.<br/>            Read/write **float**. |
| [`black_white_mode`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            Read/write [`BlackWhiteMode`](/slides/python-net/zh-hant/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/unique_id/) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code.<br/>            Because this value can be reassigned by the user or programmatically, it must not be treated<br/>            as a persistent unique key.<br/>            Read-only **int**.<br/>            See also [`Shape.office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/office_interop_shape_id/) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and<br/>            lets PowerPoint or interop code reliably reference the shape from anywhere in the document.<br/>            Read-only **int**.<br/>            See also [`Shape.unique_id`](/slides/python-net/zh-hant/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            Read/write **str**. |
| [`alternative_text_title`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            Read/write **str**. |
| [`name`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/name/) | Returns or sets the name of a shape.<br/>            Must be not None. Use empty string value if needed.<br/>            Read/write **str**. |
| [`is_decorative`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/shape_lock/) | Returns shape's locks.<br/>            Read-only [`IGraphicalObjectLock`](/slides/python-net/zh-hant/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/is_grouped/) | Determines whether the shape is grouped.<br/>            Read-only **bool**. |
| [`parent_group`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns None.<br/>            Read-only [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/slide/) | Returns the parent slide of a shape.<br/>            Read-only [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/presentation/) | Returns the parent presentation of a slide.<br/>            Read-only [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/graphical_object_lock/) | Returns shape's locks.<br/>            Read-only [`IGraphicalObjectLock`](/slides/python-net/zh-hant/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/image_type/) | Gets or sets the image type of a zoom object.<br/>            Read/write [`ZoomImageType`](/slides/python-net/zh-hant/aspose.slides/zoomimagetype).<br/>            Default value: Preview |
| [`return_to_parent`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/return_to_parent/) | Gets or sets the navigation behavior in slideshow.<br/>            Read/write **bool**.<br/>            Default value: false |
| [`show_background`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/show_background/) | Gets or sets value that specifies whether the Zoom will use the background of the destination slide.<br/>            Read/write **bool**.<br/>            Default value: true |
| [`zoom_image`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/zoom_image/) | Gets or sets image for zoom object.<br/>            Read/write [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/transition_duration/) | Gets or sets the duration of the transition between Zoom and slide.<br/>            Read/write **float**.<br/>            Default value: 1.0f |
| [`target_section`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/target_section/) | Gets or sets the section object that the Section Zoom object links to.<br/>            Read/write [`ISection`](/slides/python-net/zh-hant/aspose.slides/isection). |
| [`title`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/title/) | Returns the text title of the Summary Zoom Section object. |
| [`description`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/description/) | Returns the text description of the Summary Zoom Section object. |

## 方法

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/get_image/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/get_image/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [`write_as_svg(self, stream)`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/write_as_svg/#iorawiobase) | Saves content of Shape as SVG file. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file. |
| [`remove_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/remove_placeholder/#) | Defines that this shape isn't a placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [`get_base_placeholder(self)`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            A None is returned if the current shape is not inherited. |
| [`get_visual_bounds(self)`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection/get_visual_bounds/#) | Gets the visual bounds of the shape calculated from its rendered content. |


### 另請參閱
* 類別 [`GraphicalObject`](/slides/python-net/zh-hant/aspose.slides/graphicalobject)
* 類別 [`SectionZoomFrame`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe)
* 類別 [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)
* 類別 [`SummaryZoomSection`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection)
* 類別 [`ZoomObject`](/slides/python-net/zh-hant/aspose.slides/zoomobject)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)