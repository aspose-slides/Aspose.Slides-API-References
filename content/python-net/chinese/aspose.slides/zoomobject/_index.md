---
title: ZoomObject class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/zoomobject/
---
## ZoomObject 类

Represents an Zoom object in a slide.

**继承:**[`ZoomObject`](/slides/python-net/zh/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/zh/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/zh/aspose.slides/shape)

The ZoomObject type exposes the following members:

## 属性

| 属性 | 描述 |
| :- | :- |
| [`is_text_holder`](/slides/python-net/zh/aspose.slides/zoomobject/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            只读 **bool**. |
| [`placeholder`](/slides/python-net/zh/aspose.slides/zoomobject/placeholder/) | Returns the placeholder for a shape. Returns None if the shape has no placeholder.<br/>            只读 [`IPlaceholder`](/slides/python-net/zh/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/zh/aspose.slides/zoomobject/custom_data/) | Returns the shape's custom data.<br/>            只读 [`ICustomData`](/slides/python-net/zh/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/zh/aspose.slides/zoomobject/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            读写 [`IShapeFrame`](/slides/python-net/zh/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/zh/aspose.slides/zoomobject/frame/) | Returns or sets the shape frame's properties.<br/>            读写 [`IShapeFrame`](/slides/python-net/zh/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/zh/aspose.slides/zoomobject/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have line properties.<br/>            只读 [`ILineFormat`](/slides/python-net/zh/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/zh/aspose.slides/zoomobject/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have 3d properties.<br/>            只读 [`IThreeDFormat`](/slides/python-net/zh/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/zh/aspose.slides/zoomobject/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Note: can return None for certain types of shapes which don't have effect properties.<br/>            只读 [`IEffectFormat`](/slides/python-net/zh/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/zh/aspose.slides/zoomobject/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have fill properties.<br/>            只读 [`IFillFormat`](/slides/python-net/zh/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/zh/aspose.slides/zoomobject/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            读写 [`IHyperlink`](/slides/python-net/zh/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/zh/aspose.slides/zoomobject/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            读写 [`IHyperlink`](/slides/python-net/zh/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/zh/aspose.slides/zoomobject/hyperlink_manager/) | Returns the hyperlink manager.<br/>            只读 [`IHyperlinkManager`](/slides/python-net/zh/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/zh/aspose.slides/zoomobject/hidden/) | Determines whether the shape is hidden.<br/>            读写 **bool**. |
| [`z_order_position`](/slides/python-net/zh/aspose.slides/zoomobject/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            只读 **int**. |
| [`connection_site_count`](/slides/python-net/zh/aspose.slides/zoomobject/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            只读 **int**. |
| [`rotation`](/slides/python-net/zh/aspose.slides/zoomobject/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            读写 **float**. |
| [`x`](/slides/python-net/zh/aspose.slides/zoomobject/x/) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points.<br/>            读写 **float**. |
| [`y`](/slides/python-net/zh/aspose.slides/zoomobject/y/) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points.<br/>            读写 **float**. |
| [`width`](/slides/python-net/zh/aspose.slides/zoomobject/width/) | Gets or sets the width of the shape, measured in points.<br/>            读写 **float**. |
| [`height`](/slides/python-net/zh/aspose.slides/zoomobject/height/) | Gets or sets the height of the shape, measured in points.<br/>            读写 **float**. |
| [`black_white_mode`](/slides/python-net/zh/aspose.slides/zoomobject/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            读写 [`BlackWhiteMode`](/slides/python-net/zh/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/zh/aspose.slides/zoomobject/unique_id/) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code.<br/>            Because this value can be reassigned by the user or programmatically, it must not be treated<br/>            as a persistent unique key.<br/>            只读 **int**.<br/>            See also [`Shape.office_interop_shape_id`](/slides/python-net/zh/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/zh/aspose.slides/zoomobject/office_interop_shape_id/) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and<br/>            lets PowerPoint or interop code reliably reference the shape from anywhere in the document.<br/>            只读 **int**.<br/>            See also [`Shape.unique_id`](/slides/python-net/zh/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/zh/aspose.slides/zoomobject/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            读写 **str**. |
| [`alternative_text_title`](/slides/python-net/zh/aspose.slides/zoomobject/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            读写 **str**. |
| [`name`](/slides/python-net/zh/aspose.slides/zoomobject/name/) | Returns or sets the name of a shape.<br/>            Must be not None. Use empty string value if needed.<br/>            读写 **str**. |
| [`is_decorative`](/slides/python-net/zh/aspose.slides/zoomobject/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            读写 **bool**. |
| [`shape_lock`](/slides/python-net/zh/aspose.slides/zoomobject/shape_lock/) | Returns shape's locks.<br/>            只读 [`IGraphicalObjectLock`](/slides/python-net/zh/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/zh/aspose.slides/zoomobject/is_grouped/) | Determines whether the shape is grouped.<br/>            只读 **bool**. |
| [`parent_group`](/slides/python-net/zh/aspose.slides/zoomobject/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns None.<br/>            只读 [`IGroupShape`](/slides/python-net/zh/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/zh/aspose.slides/zoomobject/slide/) | Returns the parent slide of a shape.<br/>            只读 [`IBaseSlide`](/slides/python-net/zh/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/zh/aspose.slides/zoomobject/presentation/) | Returns the parent presentation of a slide.<br/>            只读 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/zh/aspose.slides/zoomobject/graphical_object_lock/) | Returns shape's locks.<br/>            只读 [`IGraphicalObjectLock`](/slides/python-net/zh/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/zh/aspose.slides/zoomobject/image_type/) | Gets or sets the image type of a zoom object.<br/>            读写 [`ZoomImageType`](/slides/python-net/zh/aspose.slides/zoomimagetype).<br/>            Default value: Preview |
| [`return_to_parent`](/slides/python-net/zh/aspose.slides/zoomobject/return_to_parent/) | Gets or sets the navigation behavior in slideshow.<br/>            读写 **bool**.<br/>            Default value: false |
| [`show_background`](/slides/python-net/zh/aspose.slides/zoomobject/show_background/) | Gets or sets value that specifies whether the Zoom will use the background of the destination slide.<br/>            读写 **bool**.<br/>            Default value: true |
| [`zoom_image`](/slides/python-net/zh/aspose.slides/zoomobject/zoom_image/) | Gets or sets image for zoom object.<br/>            读写 [`IPPImage`](/slides/python-net/zh/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/zh/aspose.slides/zoomobject/transition_duration/) | Gets or sets the duration of the transition between Zoom and slide.<br/>            读写 **float**.<br/>            Default value: 1.0f |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`get_image(self)`](/slides/python-net/zh/aspose.slides/zoomobject/get_image/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/zh/aspose.slides/zoomobject/get_image/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [`write_as_svg(self, stream)`](/slides/python-net/zh/aspose.slides/zoomobject/write_as_svg/#iorawiobase) | Saves content of Shape as SVG file. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/zh/aspose.slides/zoomobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file. |
| [`remove_placeholder(self)`](/slides/python-net/zh/aspose.slides/zoomobject/remove_placeholder/#) | Defines that this shape isn't a placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/zh/aspose.slides/zoomobject/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [`get_base_placeholder(self)`](/slides/python-net/zh/aspose.slides/zoomobject/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            A None is returned if the current shape is not inherited. |
| [`get_visual_bounds(self)`](/slides/python-net/zh/aspose.slides/zoomobject/get_visual_bounds/#) | Gets the visual bounds of the shape calculated from its rendered content. |

### 另请参见
* 类 [`GraphicalObject`](/slides/python-net/zh/aspose.slides/graphicalobject)
* 类 [`Shape`](/slides/python-net/zh/aspose.slides/shape)
* 类 [`ZoomObject`](/slides/python-net/zh/aspose.slides/zoomobject)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)