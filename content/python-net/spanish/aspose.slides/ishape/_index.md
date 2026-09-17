---
title: IShape class
second_title: Referencia de la API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/ishape/
---
## IShape clase

Represents a shape on a slide.

The IShape type exposes the following members:

## Propiedades

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/es/aspose.slides/ishape/is_text_holder/) | Determines whether the shape is TextHolder.<br/>            Solo lectura **bool**. |
| [`placeholder`](/slides/python-net/es/aspose.slides/ishape/placeholder/) | Returns the placeholder for a shape.<br/>            Solo lectura [`IPlaceholder`](/slides/python-net/es/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/es/aspose.slides/ishape/custom_data/) | Returns the shape's custom data.<br/>            Solo lectura [`ICustomData`](/slides/python-net/es/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/es/aspose.slides/ishape/raw_frame/) | Returns or sets the raw shape frame's properties.<br/>            Lectura/escritura [`IShapeFrame`](/slides/python-net/es/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/es/aspose.slides/ishape/frame/) | Returns or sets the shape frame's properties.<br/>            Lectura/escritura [`IShapeFrame`](/slides/python-net/es/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/es/aspose.slides/ishape/line_format/) | Returns the LineFormat object that contains line formatting properties for a shape.<br/>            Solo lectura [`ILineFormat`](/slides/python-net/es/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/es/aspose.slides/ishape/three_d_format/) | Returns the ThreeDFormat object that contains line formatting properties for a shape.<br/>            Solo lectura [`IThreeDFormat`](/slides/python-net/es/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/es/aspose.slides/ishape/effect_format/) | Returns the EffectFormat object which contains pixel effects applied to a shape.<br/>            Solo lectura [`IEffectFormat`](/slides/python-net/es/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/es/aspose.slides/ishape/fill_format/) | Returns the FillFormat object that contains fill formatting properties for a shape.<br/>            Solo lectura [`IFillFormat`](/slides/python-net/es/aspose.slides/ifillformat). |
| [`hidden`](/slides/python-net/es/aspose.slides/ishape/hidden/) | Determines whether the shape is hidden.<br/>            Lectura/escritura **bool**. |
| [`z_order_position`](/slides/python-net/es/aspose.slides/ishape/z_order_position/) | Returns the position of a shape in the z-order.<br/>            Shapes[0] returns the shape at the back of the z-order,<br/>            and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order.<br/>            Solo lectura **int**. |
| [`connection_site_count`](/slides/python-net/es/aspose.slides/ishape/connection_site_count/) | Returns the number of connection sites on the shape.<br/>            Solo lectura **int**. |
| [`rotation`](/slides/python-net/es/aspose.slides/ishape/rotation/) | Returns or sets the number of degrees the specified shape is rotated around<br/>            the z-axis. A positive value indicates clockwise rotation; a negative value<br/>            indicates counterclockwise rotation.<br/>            Lectura/escritura **float**. |
| [`x`](/slides/python-net/es/aspose.slides/ishape/x/) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points.<br/>            Lectura/escritura **float**. |
| [`y`](/slides/python-net/es/aspose.slides/ishape/y/) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points.<br/>            Lectura/escritura **float**. |
| [`width`](/slides/python-net/es/aspose.slides/ishape/width/) | Gets or sets the width of the shape, measured in points.<br/>            Lectura/escritura **float**. |
| [`height`](/slides/python-net/es/aspose.slides/ishape/height/) | Gets or sets the height of the shape, measured in points.<br/>            Lectura/escritura **float**. |
| [`alternative_text`](/slides/python-net/es/aspose.slides/ishape/alternative_text/) | Returns or sets the alternative text associated with a shape.<br/>            Lectura/escritura **str**. |
| [`alternative_text_title`](/slides/python-net/es/aspose.slides/ishape/alternative_text_title/) | Returns or sets the title of alternative text associated with a shape.<br/>            Lectura/escritura **str**. |
| [`name`](/slides/python-net/es/aspose.slides/ishape/name/) | Returns or sets the name of a shape.<br/>            Lectura/escritura **str**. |
| [`is_decorative`](/slides/python-net/es/aspose.slides/ishape/is_decorative/) | Gets or sets 'Mark as decorative' option<br/>            Lectura/escritura **bool**. |
| [`shape_lock`](/slides/python-net/es/aspose.slides/ishape/shape_lock/) | Returns shape's locks.<br/>            Solo lectura [`IBaseShapeLock`](/slides/python-net/es/aspose.slides/ibaseshapelock). |
| [`unique_id`](/slides/python-net/es/aspose.slides/ishape/unique_id/) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code.<br/>            Because this value can be reassigned by the user or programmatically, it must not be treated<br/>            as a persistent unique key.<br/>            Solo lectura **int**.<br/>            Ver también [`IShape.office_interop_shape_id`](/slides/python-net/es/aspose.slides/ishape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/es/aspose.slides/ishape/office_interop_shape_id/) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and<br/>            lets PowerPoint or interop code reliably reference the shape from anywhere in the document.<br/>            Solo lectura **int**.<br/>            Ver también [`IShape.unique_id`](/slides/python-net/es/aspose.slides/ishape/unique_id). |
| [`is_grouped`](/slides/python-net/es/aspose.slides/ishape/is_grouped/) | Determines whether the shape is grouped.<br/>            Solo lectura **bool**. |
| [`black_white_mode`](/slides/python-net/es/aspose.slides/ishape/black_white_mode/) | Property specifies how a shape will render in black-and-white display mode..<br/>            Lectura/escritura [`BlackWhiteMode`](/slides/python-net/es/aspose.slides/blackwhitemode). |
| [`parent_group`](/slides/python-net/es/aspose.slides/ishape/parent_group/) | Returns parent GroupShape object if shape is grouped. Otherwise returns None.<br/>            Solo lectura [`IGroupShape`](/slides/python-net/es/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/es/aspose.slides/ishape/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides/ishape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/es/aspose.slides/ishape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/es/aspose.slides/ishape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/es/aspose.slides/ishape/hyperlink_manager/) |  |

## Métodos

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/es/aspose.slides/ishape/get_image/#) | Returns shape thumbnail.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/es/aspose.slides/ishape/get_image/#shapethumbnailbounds-float-float) | Returns shape thumbnail. |
| [`write_as_svg(self, stream)`](/slides/python-net/es/aspose.slides/ishape/write_as_svg/#iorawiobase) | Saves content of Shape as SVG file. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/es/aspose.slides/ishape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Saves content of Shape as SVG file. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/es/aspose.slides/ishape/add_placeholder/#iplaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [`remove_placeholder(self)`](/slides/python-net/es/aspose.slides/ishape/remove_placeholder/#) | Defines that this shape isn't a placeholder. |
| [`get_base_placeholder(self)`](/slides/python-net/es/aspose.slides/ishape/get_base_placeholder/#) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).<br/>            A None is returned if the current shape is not inherited. |


### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)