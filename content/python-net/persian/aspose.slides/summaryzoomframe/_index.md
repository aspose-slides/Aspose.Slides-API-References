---
title: SummaryZoomFrame class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/summaryzoomframe/
---
## کلاس SummaryZoomFrame

یک شیء Summary Zoom را در یک اسلاید نمایش می‌دهد.

**Inheritance:** [`SummaryZoomFrame`](/slides/python-net/fa/aspose.slides/summaryzoomframe) → [`GraphicalObject`](/slides/python-net/fa/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/fa/aspose.slides/shape)

نوع SummaryZoomFrame اعضای زیر را در اختیار می‌گذارد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`is_text_holder`](/slides/python-net/fa/aspose.slides/summaryzoomframe/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            فقط-خواندنی **bool**. |
| [`placeholder`](/slides/python-net/fa/aspose.slides/summaryzoomframe/placeholder/) | Returns the placeholder for a shape. Returns None if the shape has no placeholder.<br/>            فقط-خواندنی [`IPlaceholder`](/slides/python-net/fa/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/fa/aspose.slides/summaryzoomframe/custom_data/) | Returns the shape's custom data.<br/>            فقط-خواندنی [`ICustomData`](/slides/python-net/fa/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/fa/aspose.slides/summaryzoomframe/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            خواندن/نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/fa/aspose.slides/summaryzoomframe/frame/) | Returns or sets the shape frame's properties.<br/>            خواندن/نوشتن [`IShapeFrame`](/slides/python-net/fa/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/fa/aspose.slides/summaryzoomframe/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            نکته: can return None for certain types of shapes which don't have line properties.<br/>            فقط-خواندنی [`ILineFormat`](/slides/python-net/fa/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/fa/aspose.slides/summaryzoomframe/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            نکته: can return None for certain types of shapes which don't have 3d properties.<br/>            فقط-خواندنی [`IThreeDFormat`](/slides/python-net/fa/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/fa/aspose.slides/summaryzoomframe/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            نکته: can return None for certain types of shapes which don't have effect properties.<br/>            فقط-خواندنی [`IEffectFormat`](/slides/python-net/fa/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/fa/aspose.slides/summaryzoomframe/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            نکته: can return None for certain types of shapes which don't have fill properties.<br/>            فقط-خواندنی [`IFillFormat`](/slides/python-net/fa/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/fa/aspose.slides/summaryzoomframe/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            خواندن/نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/fa/aspose.slides/summaryzoomframe/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            خواندن/نوشتن [`IHyperlink`](/slides/python-net/fa/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/fa/aspose.slides/summaryzoomframe/hyperlink_manager/) | Returns the hyperlink manager.<br/>            فقط-خواندنی [`IHyperlinkManager`](/slides/python-net/fa/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/fa/aspose.slides/summaryzoomframe/hidden/) | Determines whether the shape is hidden.<br/>            خواندن/نوشتن **bool**. |
| [`z_order_position`](/slides/python-net/fa/aspose.slides/summaryzoomframe/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            فقط-خواندنی **int**. |
| [`connection_site_count`](/slides/python-net/fa/aspose.slides/summaryzoomframe/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            فقط-خواندنی **int**. |
| [`rotation`](/slides/python-net/fa/aspose.slides/summaryzoomframe/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            خواندن/نوشتن **float**. |
| [`x`](/slides/python-net/fa/aspose.slides/summaryzoomframe/x/) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points.<br/>            خواندن/نوشتن **float**. |
| [`y`](/slides/python-net/fa/aspose.slides/summaryzoomframe/y/) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points.<br/>            خواندن/نوشتن **float**. |
| [`width`](/slides/python-net/fa/aspose.slides/summaryzoomframe/width/) | Gets or sets the width of the shape, measured in points.<br/>            خواندن/نوشتن **float**. |
| [`height`](/slides/python-net/fa/aspose.slides/summaryzoomframe/height/) | Gets or sets the height of the shape, measured in points.<br/>            خواندن/نوشتن **float**. |
| [`black_white_mode`](/slides/python-net/fa/aspose.slides/summaryzoomframe/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            خواندن/نوشتن [`BlackWhiteMode`](/slides/python-net/fa/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/fa/aspose.slides/summaryzoomframe/unique_id/) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code.<br/>            Because this value can be reassigned by the user or programmatically, it must not be treated<br/>            as a persistent unique key.<br/>            فقط-خواندنی **int**.<br/>            همچنین ببینید [`Shape.office_interop_shape_id`](/slides/python-net/fa/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/fa/aspose.slides/summaryzoomframe/office_interop_shape_id/) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and<br/>            lets PowerPoint or interop code reliably reference the shape from anywhere in the document.<br/>            فقط-خواندنی **int**.<br/>            همچنین ببینید [`Shape.unique_id`](/slides/python-net/fa/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/fa/aspose.slides/summaryzoomframe/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            خواندن/نوشتن **str**. |
| [`alternative_text_title`](/slides/python-net/fa/aspose.slides/summaryzoomframe/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            خواندن/نوشتن **str**. |
| [`name`](/slides/python-net/fa/aspose.slides/summaryzoomframe/name/) | Returns or sets the name of a shape.<br/>            Must be not None. Use empty string value if needed.<br/>            خواندن/نوشتن **str**. |
| [`is_decorative`](/slides/python-net/fa/aspose.slides/summaryzoomframe/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            خواندن/نوشتن **bool**. |
| [`shape_lock`](/slides/python-net/fa/aspose.slides/summaryzoomframe/shape_lock/) | Returns shape's locks.<br/>            فقط-خواندنی [`IGraphicalObjectLock`](/slides/python-net/fa/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/fa/aspose.slides/summaryzoomframe/is_grouped/) | Determines whether the shape is grouped.<br/>            فقط-خواندنی **bool**. |
| [`parent_group`](/slides/python-net/fa/aspose.slides/summaryzoomframe/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns None.<br/>            فقط-خواندنی [`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/fa/aspose.slides/summaryzoomframe/slide/) | Returns the parent slide of a shape.<br/>            فقط-خواندنی [`IBaseSlide`](/slides/python-net/fa/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fa/aspose.slides/summaryzoomframe/presentation/) | Returns the parent presentation of a slide.<br/>            فقط-خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/fa/aspose.slides/summaryzoomframe/graphical_object_lock/) | Returns shape's locks.<br/>            فقط-خواندنی [`IGraphicalObjectLock`](/slides/python-net/fa/aspose.slides/igraphicalobjectlock). |
| [`layout`](/slides/python-net/fa/aspose.slides/summaryzoomframe/layout/) | Gets layout of Summary Zoom Sections in the frame.<br/>            Default value is GridLayout. |
| [`summary_zoom_collection`](/slides/python-net/fa/aspose.slides/summaryzoomframe/summary_zoom_collection/) | Gets [`ISummaryZoomSectionCollection`](/slides/python-net/fa/aspose.slides/isummaryzoomsectioncollection) for the Summary Zoom Frame object. |

## متدها

| متد | توضیح |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fa/aspose.slides/summaryzoomframe/get_image/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fa/aspose.slides/summaryzoomframe/get_image/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [`write_as_svg(self, stream)`](/slides/python-net/fa/aspose.slides/summaryzoomframe/write_as_svg/#iorawiobase) | Saves content of Shape as SVG file. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fa/aspose.slides/summaryzoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file. |
| [`remove_placeholder(self)`](/slides/python-net/fa/aspose.slides/summaryzoomframe/remove_placeholder/#) | Defines that this shape isn't a placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fa/aspose.slides/summaryzoomframe/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [`get_base_placeholder(self)`](/slides/python-net/fa/aspose.slides/summaryzoomframe/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            A None is returned if the current shape is not inherited. |
| [`get_visual_bounds(self)`](/slides/python-net/fa/aspose.slides/summaryzoomframe/get_visual_bounds/#) | Gets the visual bounds of the shape calculated from its rendered content. |

### موارد مرتبط
* کلاس [`GraphicalObject`](/slides/python-net/fa/aspose.slides/graphicalobject)
* کلاس [`Shape`](/slides/python-net/fa/aspose.slides/shape)
* کلاس [`SummaryZoomFrame`](/slides/python-net/fa/aspose.slides/summaryzoomframe)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)