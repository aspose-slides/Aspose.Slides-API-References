---
title: IAutoShape class
second_title: Referencia de API Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/iautoshape/
---
## IAutoShape clase

Representa un AutoShape.

El tipo IAutoShape expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`shape_lock`](/slides/python-net/es/aspose.slides/iautoshape/shape_lock/) | Devuelve los bloqueos de la forma.<br/>            Solo lectura [`IAutoShapeLock`](/slides/python-net/es/aspose.slides/iautoshapelock). |
| [`auto_shape_lock`](/slides/python-net/es/aspose.slides/iautoshape/auto_shape_lock/) | Devuelve los bloqueos del AutoShape.<br/>            Solo lectura [`IAutoShapeLock`](/slides/python-net/es/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/es/aspose.slides/iautoshape/text_frame/) | Devuelve el objeto TextFrame para el AutoShape.<br/>            Solo lectura [`ITextFrame`](/slides/python-net/es/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/es/aspose.slides/iautoshape/use_background_fill/) | Determina si este autoshape debe rellenarse con el relleno de fondo de la diapositiva en lugar de lo especificado por el estilo o el formato de relleno.<br/>            Lectura/escritura **bool**. |
| [`is_text_box`](/slides/python-net/es/aspose.slides/iautoshape/is_text_box/) | Especifica si la forma es un cuadro de texto. |
| [`shape_style`](/slides/python-net/es/aspose.slides/iautoshape/shape_style/) |  |
| [`shape_type`](/slides/python-net/es/aspose.slides/iautoshape/shape_type/) |  |
| [`adjustments`](/slides/python-net/es/aspose.slides/iautoshape/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/es/aspose.slides/iautoshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/es/aspose.slides/iautoshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/es/aspose.slides/iautoshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/es/aspose.slides/iautoshape/raw_frame/) |  |
| [`frame`](/slides/python-net/es/aspose.slides/iautoshape/frame/) |  |
| [`line_format`](/slides/python-net/es/aspose.slides/iautoshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/es/aspose.slides/iautoshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/es/aspose.slides/iautoshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/es/aspose.slides/iautoshape/fill_format/) |  |
| [`hidden`](/slides/python-net/es/aspose.slides/iautoshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/es/aspose.slides/iautoshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/es/aspose.slides/iautoshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/es/aspose.slides/iautoshape/rotation/) |  |
| [`x`](/slides/python-net/es/aspose.slides/iautoshape/x/) |  |
| [`y`](/slides/python-net/es/aspose.slides/iautoshape/y/) |  |
| [`width`](/slides/python-net/es/aspose.slides/iautoshape/width/) |  |
| [`height`](/slides/python-net/es/aspose.slides/iautoshape/height/) |  |
| [`alternative_text`](/slides/python-net/es/aspose.slides/iautoshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/es/aspose.slides/iautoshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/es/aspose.slides/iautoshape/name/) |  |
| [`is_decorative`](/slides/python-net/es/aspose.slides/iautoshape/is_decorative/) |  |
| [`unique_id`](/slides/python-net/es/aspose.slides/iautoshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/es/aspose.slides/iautoshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/es/aspose.slides/iautoshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/es/aspose.slides/iautoshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/es/aspose.slides/iautoshape/parent_group/) |  |
| [`slide`](/slides/python-net/es/aspose.slides/iautoshape/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides/iautoshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/es/aspose.slides/iautoshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/es/aspose.slides/iautoshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/es/aspose.slides/iautoshape/hyperlink_manager/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`get_image(self)`](/slides/python-net/es/aspose.slides/iautoshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/es/aspose.slides/iautoshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/es/aspose.slides/iautoshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/es/aspose.slides/iautoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`add_text_frame(self, text)`](/slides/python-net/es/aspose.slides/iautoshape/add_text_frame/#str) | Agrega un nuevo TextFrame a una forma.<br/>            Si la forma ya tiene TextFrame, simplemente cambia su texto. |
| [`get_geometry_paths(self)`](/slides/python-net/es/aspose.slides/iautoshape/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/es/aspose.slides/iautoshape/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/es/aspose.slides/iautoshape/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/es/aspose.slides/iautoshape/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/es/aspose.slides/iautoshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/es/aspose.slides/iautoshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/es/aspose.slides/iautoshape/get_base_placeholder/#) |  |


### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)