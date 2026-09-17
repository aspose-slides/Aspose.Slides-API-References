---
title: IPictureFrame class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/ipictureframe/
---
## IPictureFrame clase

Representa un marco con una imagen dentro.

El tipo IPictureFrame expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`shape_lock`](/slides/python-net/es/aspose.slides/ipictureframe/shape_lock/) | Devuelve los bloqueos de la forma.<br/>            Solo lectura [`IPictureFrameLock`](/slides/python-net/es/aspose.slides/ipictureframelock). |
| [`picture_frame_lock`](/slides/python-net/es/aspose.slides/ipictureframe/picture_frame_lock/) | Devuelve los bloqueos de PictureFrame.<br/>            Solo lectura [`IPictureFrameLock`](/slides/python-net/es/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/es/aspose.slides/ipictureframe/picture_format/) | Devuelve el objeto PictureFillFormat para un marco de imagen.<br/>            Solo lectura [`IPictureFillFormat`](/slides/python-net/es/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/es/aspose.slides/ipictureframe/relative_scale_height/) | Devuelve o establece la escala de altura (relativa al tamaño original de la imagen) del marco de imagen. El valor 1.0 corresponde al 100%.<br/>            Lectura/escritura **float**. |
| [`relative_scale_width`](/slides/python-net/es/aspose.slides/ipictureframe/relative_scale_width/) | Devuelve o establece la escala de ancho (relativa al tamaño original de la imagen) del marco de imagen. El valor 1.0 corresponde al 100%.<br/>            Lectura/escritura **float**. |
| [`shape_style`](/slides/python-net/es/aspose.slides/ipictureframe/shape_style/) |  |
| [`shape_type`](/slides/python-net/es/aspose.slides/ipictureframe/shape_type/) |  |
| [`adjustments`](/slides/python-net/es/aspose.slides/ipictureframe/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/es/aspose.slides/ipictureframe/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/es/aspose.slides/ipictureframe/placeholder/) |  |
| [`custom_data`](/slides/python-net/es/aspose.slides/ipictureframe/custom_data/) |  |
| [`raw_frame`](/slides/python-net/es/aspose.slides/ipictureframe/raw_frame/) |  |
| [`frame`](/slides/python-net/es/aspose.slides/ipictureframe/frame/) |  |
| [`line_format`](/slides/python-net/es/aspose.slides/ipictureframe/line_format/) |  |
| [`three_d_format`](/slides/python-net/es/aspose.slides/ipictureframe/three_d_format/) |  |
| [`effect_format`](/slides/python-net/es/aspose.slides/ipictureframe/effect_format/) |  |
| [`fill_format`](/slides/python-net/es/aspose.slides/ipictureframe/fill_format/) |  |
| [`hidden`](/slides/python-net/es/aspose.slides/ipictureframe/hidden/) |  |
| [`z_order_position`](/slides/python-net/es/aspose.slides/ipictureframe/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/es/aspose.slides/ipictureframe/connection_site_count/) |  |
| [`rotation`](/slides/python-net/es/aspose.slides/ipictureframe/rotation/) |  |
| [`x`](/slides/python-net/es/aspose.slides/ipictureframe/x/) |  |
| [`y`](/slides/python-net/es/aspose.slides/ipictureframe/y/) |  |
| [`width`](/slides/python-net/es/aspose.slides/ipictureframe/width/) |  |
| [`height`](/slides/python-net/es/aspose.slides/ipictureframe/height/) |  |
| [`alternative_text`](/slides/python-net/es/aspose.slides/ipictureframe/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/es/aspose.slides/ipictureframe/alternative_text_title/) |  |
| [`name`](/slides/python-net/es/aspose.slides/ipictureframe/name/) |  |
| [`is_decorative`](/slides/python-net/es/aspose.slides/ipictureframe/is_decorative/) |  |
| [`unique_id`](/slides/python-net/es/aspose.slides/ipictureframe/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/es/aspose.slides/ipictureframe/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/es/aspose.slides/ipictureframe/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/es/aspose.slides/ipictureframe/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/es/aspose.slides/ipictureframe/parent_group/) |  |
| [`slide`](/slides/python-net/es/aspose.slides/ipictureframe/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides/ipictureframe/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/es/aspose.slides/ipictureframe/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/es/aspose.slides/ipictureframe/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/es/aspose.slides/ipictureframe/hyperlink_manager/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`get_image(self)`](/slides/python-net/es/aspose.slides/ipictureframe/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/es/aspose.slides/ipictureframe/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/es/aspose.slides/ipictureframe/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/es/aspose.slides/ipictureframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/es/aspose.slides/ipictureframe/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/es/aspose.slides/ipictureframe/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/es/aspose.slides/ipictureframe/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/es/aspose.slides/ipictureframe/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/es/aspose.slides/ipictureframe/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/es/aspose.slides/ipictureframe/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/es/aspose.slides/ipictureframe/get_base_placeholder/#) |  |


### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)