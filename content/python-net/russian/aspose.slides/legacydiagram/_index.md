---
title: LegacyDiagram class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/legacydiagram/
---
## LegacyDiagram класс

Represents a legacy diagram object.

**Inheritance:**[`LegacyDiagram`](/slides/python-net/ru/aspose.slides/legacydiagram) → [`GraphicalObject`](/slides/python-net/ru/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/ru/aspose.slides/shape)

The LegacyDiagram type exposes the following members:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`is_text_holder`](/slides/python-net/ru/aspose.slides/legacydiagram/is_text_holder/) | Determines whether the shape is TextHolder_PPT.<br/>            Толькочтение **bool**. |
| [`placeholder`](/slides/python-net/ru/aspose.slides/legacydiagram/placeholder/) | Returns the placeholder for a shape. Returns None if the shape has no placeholder.<br/>            Толькочтение [`IPlaceholder`](/slides/python-net/ru/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/ru/aspose.slides/legacydiagram/custom_data/) | Returns the shape's custom data.<br/>            Толькочтение [`ICustomData`](/slides/python-net/ru/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/ru/aspose.slides/legacydiagram/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/ru/aspose.slides/legacydiagram/frame/) | Returns or sets the shape frame's properties.<br/>            Чтение/запись [`IShapeFrame`](/slides/python-net/ru/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/ru/aspose.slides/legacydiagram/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have line properties.<br/>            Толькочтение [`ILineFormat`](/slides/python-net/ru/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/ru/aspose.slides/legacydiagram/three_d_format/) | Returns the ThreeDFormat object that 3d effect properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have 3d properties.<br/>            Толькочтение [`IThreeDFormat`](/slides/python-net/ru/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/ru/aspose.slides/legacydiagram/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Note: can return None for certain types of shapes which don't have effect properties.<br/>            Толькочтение [`IEffectFormat`](/slides/python-net/ru/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/ru/aspose.slides/legacydiagram/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Note: can return None for certain types of shapes which don't have fill properties.<br/>            Толькочтение [`IFillFormat`](/slides/python-net/ru/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/ru/aspose.slides/legacydiagram/hyperlink_click/) | Returns or sets the hyperlink defined for mouse click.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/ru/aspose.slides/legacydiagram/hyperlink_mouse_over/) | Returns or sets the hyperlink defined for mouse over.<br/>            Чтение/запись [`IHyperlink`](/slides/python-net/ru/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/ru/aspose.slides/legacydiagram/hyperlink_manager/) | Returns the hyperlink manager.<br/>            Толькочтение [`IHyperlinkManager`](/slides/python-net/ru/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/ru/aspose.slides/legacydiagram/hidden/) | Determines whether the shape is hidden.<br/>            Чтение/запись **bool**. |
| [`z_order_position`](/slides/python-net/ru/aspose.slides/legacydiagram/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Толькочтение **int**. |
| [`connection_site_count`](/slides/python-net/ru/aspose.slides/legacydiagram/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            Толькочтение **int**. |
| [`rotation`](/slides/python-net/ru/aspose.slides/legacydiagram/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Чтение/запись **float**. |
| [`x`](/slides/python-net/ru/aspose.slides/legacydiagram/x/) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points.<br/>            Чтение/запись **float**. |
| [`y`](/slides/python-net/ru/aspose.slides/legacydiagram/y/) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points.<br/>            Чтение/запись **float**. |
| [`width`](/slides/python-net/ru/aspose.slides/legacydiagram/width/) | Gets or sets the width of the shape, measured in points.<br/>            Чтение/запись **float**. |
| [`height`](/slides/python-net/ru/aspose.slides/legacydiagram/height/) | Gets or sets the height of the shape, measured in points.<br/>            Чтение/запись **float**. |
| [`black_white_mode`](/slides/python-net/ru/aspose.slides/legacydiagram/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            Чтение/запись [`BlackWhiteMode`](/slides/python-net/ru/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/ru/aspose.slides/legacydiagram/unique_id/) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code.<br/>            Because this value can be reassigned by the user or programmatically, it must not be treated<br/>            as a persistent unique key.<br/>            Толькочтение **int**.<br/>            See also [`Shape.office_interop_shape_id`](/slides/python-net/ru/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/ru/aspose.slides/legacydiagram/office_interop_shape_id/) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and<br/>            lets PowerPoint or interop code reliably reference the shape from anywhere in the document.<br/>            Толькочтение **int**.<br/>            See also [`Shape.unique_id`](/slides/python-net/ru/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/ru/aspose.slides/legacydiagram/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            Чтение/запись **str**. |
| [`alternative_text_title`](/slides/python-net/ru/aspose.slides/legacydiagram/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            Чтение/запись **str**. |
| [`name`](/slides/python-net/ru/aspose.slides/legacydiagram/name/) | Returns or sets the name of a shape.<br/>            Must be not None. Use empty string value if needed.<br/>            Чтение/запись **str**. |
| [`is_decorative`](/slides/python-net/ru/aspose.slides/legacydiagram/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Чтение/запись **bool**. |
| [`shape_lock`](/slides/python-net/ru/aspose.slides/legacydiagram/shape_lock/) | Returns shape's locks.<br/>            Толькочтение [`IGraphicalObjectLock`](/slides/python-net/ru/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/ru/aspose.slides/legacydiagram/is_grouped/) | Determines whether the shape is grouped.<br/>            Толькочтение **bool**. |
| [`parent_group`](/slides/python-net/ru/aspose.slides/legacydiagram/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns None.<br/>            Толькочтение [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/ru/aspose.slides/legacydiagram/slide/) | Returns the parent slide of a shape.<br/>            Толькочтение [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ru/aspose.slides/legacydiagram/presentation/) | Returns the parent presentation of a slide.<br/>            Толькочтение [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/ru/aspose.slides/legacydiagram/graphical_object_lock/) | Returns shape's locks.<br/>            Толькочтение [`IGraphicalObjectLock`](/slides/python-net/ru/aspose.slides/igraphicalobjectlock). |

## Методы

| Метод | Описание |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ru/aspose.slides/legacydiagram/get_image/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/ru/aspose.slides/legacydiagram/get_image/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [`write_as_svg(self, stream)`](/slides/python-net/ru/aspose.slides/legacydiagram/write_as_svg/#iorawiobase) | Saves content of Shape as SVG file. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/ru/aspose.slides/legacydiagram/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file. |
| [`remove_placeholder(self)`](/slides/python-net/ru/aspose.slides/legacydiagram/remove_placeholder/#) | Defines that this shape isn't a placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/ru/aspose.slides/legacydiagram/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [`get_base_placeholder(self)`](/slides/python-net/ru/aspose.slides/legacydiagram/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            A None is returned if the current shape is not inherited. |
| [`get_visual_bounds(self)`](/slides/python-net/ru/aspose.slides/legacydiagram/get_visual_bounds/#) | Gets the visual bounds of the shape calculated from its rendered content. |
| [`convert_to_smart_art(self)`](/slides/python-net/ru/aspose.slides/legacydiagram/convert_to_smart_art/#) | Converts legacy digram to editable SmartArt object. <br/>            Created SmartArt object adds to parent group shape at the same position. |
| [`convert_to_group_shape(self)`](/slides/python-net/ru/aspose.slides/legacydiagram/convert_to_group_shape/#) | Converts legacy digram to editable group shape. <br/>            Created GroupShape object adds to parent group shape at the same position. |


### См. также
* класс [`GraphicalObject`](/slides/python-net/ru/aspose.slides/graphicalobject)
* класс [`LegacyDiagram`](/slides/python-net/ru/aspose.slides/legacydiagram)
* класс [`Shape`](/slides/python-net/ru/aspose.slides/shape)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)