---
title: GroupShape class
second_title: Aspose.Slides للغة Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/groupshape/
---
## الفئة GroupShape

Represents a group of shapes on a slide.

**Inheritance:**[`GroupShape`](/slides/python-net/ar/aspose.slides/groupshape) → [`Shape`](/slides/python-net/ar/aspose.slides/shape)

The GroupShape type exposes the following members:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ar/aspose.slides/groupshape/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            قراءة فقط **bool**. |
| [`placeholder`](/slides/python-net/ar/aspose.slides/groupshape/placeholder/) | Returns the placeholder for a shape. Returns None if the shape has no placeholder.<br/>            قراءة فقط [`IPlaceholder`](/slides/python-net/ar/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ar/aspose.slides/groupshape/custom_data/) | Returns the shape's custom data.<br/>            قراءة فقط [`ICustomData`](/slides/python-net/ar/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ar/aspose.slides/groupshape/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ar/aspose.slides/groupshape/frame/) | Returns or sets the shape frame's properties.<br/>            قراءة/كتابة [`IShapeFrame`](/slides/python-net/ar/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ar/aspose.slides/groupshape/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            ملاحظة: Returns None for GroupShape objects because they don't have line properties.<br/>            قراءة فقط [`ILineFormat`](/slides/python-net/ar/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ar/aspose.slides/groupshape/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            ملاحظة: can return None for certain types of shapes which don't have 3d properties.<br/>            قراءة فقط [`IThreeDFormat`](/slides/python-net/ar/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ar/aspose.slides/groupshape/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            ملاحظة: can return None for certain types of shapes which don't have effect properties.<br/>            قراءة فقط [`IEffectFormat`](/slides/python-net/ar/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ar/aspose.slides/groupshape/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            ملاحظة: can return None for certain types of shapes which don't have fill properties.<br/>            قراءة فقط [`IFillFormat`](/slides/python-net/ar/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ar/aspose.slides/groupshape/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ar/aspose.slides/groupshape/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            قراءة/كتابة [`IHyperlink`](/slides/python-net/ar/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ar/aspose.slides/groupshape/hyperlink_manager/) | Returns the hyperlink manager.<br/>            قراءة فقط [`IHyperlinkManager`](/slides/python-net/ar/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ar/aspose.slides/groupshape/hidden/) | Determines whether the shape is hidden.<br/>            قراءة/كتابة **bool**. |
| [`z_order_position`](/slides/python-net/ar/aspose.slides/groupshape/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            قراءة فقط **int**. |
| [`connection_site_count`](/slides/python-net/ar/aspose.slides/groupshape/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            قراءة فقط **int**. |
| [`rotation`](/slides/python-net/ar/aspose.slides/groupshape/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            قراءة/كتابة **float**. |
| [`x`](/slides/python-net/ar/aspose.slides/groupshape/x/) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points.<br/>            قراءة/كتابة **float**. |
| [`y`](/slides/python-net/ar/aspose.slides/groupshape/y/) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points.<br/>            قراءة/كتابة **float**. |
| [`width`](/slides/python-net/ar/aspose.slides/groupshape/width/) | Gets or sets the width of the shape, measured in points.<br/>            قراءة/كتابة **float**. |
| [`height`](/slides/python-net/ar/aspose.slides/groupshape/height/) | Gets or sets the height of the shape, measured in points.<br/>            قراءة/كتابة **float**. |
| [`black_white_mode`](/slides/python-net/ar/aspose.slides/groupshape/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            قراءة/كتابة [`BlackWhiteMode`](/slides/python-net/ar/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ar/aspose.slides/groupshape/unique_id/) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code.<br/>            Because this value can be reassigned by the user or programmatically, it must not be treated<br/>            as a persistent unique key.<br/>            قراءة فقط **int**.<br/>            See also [`Shape.office_interop_shape_id`](/slides/python-net/ar/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ar/aspose.slides/groupshape/office_interop_shape_id/) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and<br/>            lets PowerPoint or interop code reliably reference the shape from anywhere in the document.<br/>            قراءة فقط **int**.<br/>            See also [`Shape.unique_id`](/slides/python-net/ar/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ar/aspose.slides/groupshape/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            قراءة/كتابة **str**. |
| [`alternative_text_title`](/slides/python-net/ar/aspose.slides/groupshape/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            قراءة/كتابة **str**. |
| [`name`](/slides/python-net/ar/aspose.slides/groupshape/name/) | Returns or sets the name of a shape.<br/>            Must be not None. Use empty string value if needed.<br/>            قراءة/كتابة **str**. |
| [`is_decorative`](/slides/python-net/ar/aspose.slides/groupshape/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            قراءة/كتابة **bool**. |
| [`shape_lock`](/slides/python-net/ar/aspose.slides/groupshape/shape_lock/) | Returns shape's locks.<br/>            قراءة فقط [`IGroupShapeLock`](/slides/python-net/ar/aspose.slides/igroupshapelock). |
| [`is_grouped`](/slides/python-net/ar/aspose.slides/groupshape/is_grouped/) | Determines whether the shape is grouped.<br/>            قراءة فقط **bool**. |
| [`parent_group`](/slides/python-net/ar/aspose.slides/groupshape/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns None.<br/>            قراءة فقط [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ar/aspose.slides/groupshape/slide/) | Returns the parent slide of a shape.<br/>            قراءة فقط [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ar/aspose.slides/groupshape/presentation/) | Returns the parent presentation of a slide.<br/>            قراءة فقط [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). |
| [`group_shape_lock`](/slides/python-net/ar/aspose.slides/groupshape/group_shape_lock/) | Returns shape's locks.<br/>            قراءة فقط [`IGroupShapeLock`](/slides/python-net/ar/aspose.slides/igroupshapelock). |
| [`shapes`](/slides/python-net/ar/aspose.slides/groupshape/shapes/) | Returns the collection of shapes inside the group.<br/>            قراءة فقط [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection). |

## الأساليب

| الطريقة | الوصف |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ar/aspose.slides/groupshape/get_image/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ar/aspose.slides/groupshape/get_image/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [`write_as_svg(self, stream)`](/slides/python-net/ar/aspose.slides/groupshape/write_as_svg/#iorawiobase) | Saves content of Shape as SVG file. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ar/aspose.slides/groupshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file. |
| [`remove_placeholder(self)`](/slides/python-net/ar/aspose.slides/groupshape/remove_placeholder/#) | Defines that this shape isn't a placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ar/aspose.slides/groupshape/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [`get_base_placeholder(self)`](/slides/python-net/ar/aspose.slides/groupshape/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            A None is returned if the current shape is not inherited. |
| [`get_visual_bounds(self)`](/slides/python-net/ar/aspose.slides/groupshape/get_visual_bounds/#) | Gets the visual bounds of the shape calculated from its rendered content. |

### انظر أيضًا
* فئة [`GroupShape`](/slides/python-net/ar/aspose.slides/groupshape)
* فئة [`Shape`](/slides/python-net/ar/aspose.slides/shape)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)