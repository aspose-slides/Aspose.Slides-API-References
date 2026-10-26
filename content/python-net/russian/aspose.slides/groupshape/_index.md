---
title: GroupShape class
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/groupshape/
---
## GroupShape класс

Represents a group of shapes on a slide.

**Inheritance:**[`GroupShape`](/slides/python-net/ru/aspose.slides/groupshape) → [`Shape`](/slides/python-net/ru/aspose.slides/shape)

The GroupShape type exposes the following members:

## Свойства

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ru/aspose.slides/groupshape/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            Только для чтения **bool**. |
| [`placeholder`](/slides/python-net/ru/aspose.slides/groupshape/placeholder/) | Returns the placeholder for a shape. Returns None if the shape has no placeholder.<br/>            Только для чтения [`IPlaceholder`](/slides/python-net/ru/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ru/aspose.slides/groupshape/custom_data/) | Returns the shape's custom data.<br/>            Только для чтения [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ru/aspose.slides/groupshape/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ru/aspose.slides/groupshape/frame/) | Returns or sets the shape frame's properties.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ru/aspose.slides/groupshape/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Примечание: Returns None for GroupShape objects because they don't have line properties.<br/>            Только для чтения [`ILineFormat`](/slides/python-net/ru/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ru/aspose.slides/groupshape/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Примечание: can return None for certain types of shapes which don't have 3d properties.<br/>            Только для чтения [`IThreeDFormat`](/slides/python-net/ru/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ru/aspose.slides/groupshape/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Примечание: can return None for certain types of shapes which don't have effect properties.<br/>            Только для чтения [`IEffectFormat`](/slides/python-net/ru/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ru/aspose.slides/groupshape/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Примечание: can return None for certain types of shapes which don't have fill properties.<br/>            Только для чтения [`IFillFormat`](/slides/python-net/ru/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ru/aspose.slides/groupshape/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ru/aspose.slides/groupshape/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ru/aspose.slides/groupshape/hyperlink_manager/) | Returns the hyperlink manager.<br/>            Только для чтения [`IHyperlinkManager`](/slides/python-net/ru/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ru/aspose.slides/groupshape/hidden/) | Determines whether the shape is hidden.<br/>            Чтение/запись **bool**. |
| [`z_order_position`](/slides/python-net/ru/aspose.slides/groupshape/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Только для чтения **int**. |
| [`connection_site_count`](/slides/python-net/ru/aspose.slides/groupshape/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            Только для чтения **int**. |
| [`rotation`](/slides/python-net/ru/aspose.slides/groupshape/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Чтение/запись **float**. |
| [`x`](/slides/python-net/ru/aspose.slides/groupshape/x/) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points.<br/>            Чтение/запись **float**. |
| [`y`](/slides/python-net/ru/aspose.slides/groupshape/y/) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points.<br/>            Чтение/запись **float**. |
| [`width`](/slides/python-net/ru/aspose.slides/groupshape/width/) | Gets or sets the width of the shape, measured in points.<br/>            Чтение/запись **float**. |
| [`height`](/slides/python-net/ru/aspose.slides/groupshape/height/) | Gets or sets the height of the shape, measured in points.<br/>            Чтение/запись **float**. |
| [`black_white_mode`](/slides/python-net/ru/aspose.slides/groupshape/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            Чтение/запись [`BlackWhiteMode`](/slides/python-net/ru/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ru/aspose.slides/groupshape/unique_id/) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code.<br/>            Because this value can be reassigned by the user or programmatically, it must not be treated<br/>            as a persistent unique key.<br/>            Только для чтения **int**.<br/>            See also [`Shape.office_interop_shape_id`](/slides/python-net/ru/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ru/aspose.slides/groupshape/office_interop_shape_id/) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and<br/>            lets PowerPoint or interop code reliably reference the shape from anywhere in the document.<br/>            Только для чтения **int**.<br/>            See also [`Shape.unique_id`](/slides/python-net/ru/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ru/aspose.slides/groupshape/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            Чтение/запись **str**. |
| [`alternative_text_title`](/slides/python-net/ru/aspose.slides/groupshape/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            Чтение/запись **str**. |
| [`name`](/slides/python-net/ru/aspose.slides/groupshape/name/) | Returns or sets the name of a shape.<br/>            Must be not None. Use empty string value if needed.<br/>            Чтение/запись **str**. |
| [`is_decorative`](/slides/python-net/ru/aspose.slides/groupshape/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Чтение/запись **bool**. |
| [`shape_lock`](/slides/python-net/ru/aspose.slides/groupshape/shape_lock/) | Returns shape's locks.<br/>            Только для чтения [`IGroupShapeLock`](/slides/python-net/ru/aspose.slides/igroupshapelock). |
| [`is_grouped`](/slides/python-net/ru/aspose.slides/groupshape/is_grouped/) | Determines whether the shape is grouped.<br/>            Только для чтения **bool**. |
| [`parent_group`](/slides/python-net/ru/aspose.slides/groupshape/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns None.<br/>            Только для чтения [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ru/aspose.slides/groupshape/slide/) | Returns the parent slide of a shape.<br/>            Только для чтения [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ru/aspose.slides/groupshape/presentation/) | Returns the parent presentation of a slide.<br/>            Только для чтения [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). |
| [`group_shape_lock`](/slides/python-net/ru/aspose.slides/groupshape/group_shape_lock/) | Returns shape's locks.<br/>            Только для чтения [`IGroupShapeLock`](/slides/python-net/ru/aspose.slides/igroupshapelock). |
| [`shapes`](/slides/python-net/ru/aspose.slides/groupshape/shapes/) | Returns the collection of shapes inside the group.<br/>            Только для чтения [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection). |

## Методы

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ru/aspose.slides/groupshape/get_image/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/groupshape/get_image/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [`write_as_svg(self, stream)`](/slides/python-net/ru/aspose.slides/groupshape/write_as_svg/#iorawiobase) | Saves content of Shape as SVG file. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ru/aspose.slides/groupshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file. |
| [`remove_placeholder(self)`](/slides/python-net/ru/aspose.slides/groupshape/remove_placeholder/#) | Defines that this shape isn't a placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ru/aspose.slides/groupshape/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [`get_base_placeholder(self)`](/slides/python-net/ru/aspose.slides/groupshape/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            A None is returned if the current shape is not inherited. |
| [`get_visual_bounds(self)`](/slides/python-net/ru/aspose.slides/groupshape/get_visual_bounds/#) | Gets the visual bounds of the shape calculated from its rendered content. |

### Смотрите также
* класс [`GroupShape`](/slides/python-net/ru/aspose.slides/groupshape)
* класс [`Shape`](/slides/python-net/ru/aspose.slides/shape)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)