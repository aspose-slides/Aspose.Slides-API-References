---
title: IAutoShape class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/iautoshape/
---
## IAutoShape classe

Representa um AutoShape.

O tipo IAutoShape expõe os seguintes membros:

## Propriedades

| Property | Description |
| :- | :- |
| [`shape_lock`](/slides/python-net/pt/aspose.slides/iautoshape/shape_lock/) | Retorna os bloqueios da forma.<br/>            Somente leitura [`IAutoShapeLock`](/slides/python-net/pt/aspose.slides/iautoshapelock). |
| [`auto_shape_lock`](/slides/python-net/pt/aspose.slides/iautoshape/auto_shape_lock/) | Retorna os bloqueios do AutoShape.<br/>            Somente leitura [`IAutoShapeLock`](/slides/python-net/pt/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/pt/aspose.slides/iautoshape/text_frame/) | Retorna o objeto TextFrame para o AutoShape.<br/>            Somente leitura [`ITextFrame`](/slides/python-net/pt/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/pt/aspose.slides/iautoshape/use_background_fill/) | Determina se este autoshape deve ser preenchido com o fundo do slide em vez do especificado por estilo ou formato de preenchimento.<br/>            Leitura/gravação **bool**. |
| [`is_text_box`](/slides/python-net/pt/aspose.slides/iautoshape/is_text_box/) | Especifica se a forma é uma caixa de texto. |
| [`shape_style`](/slides/python-net/pt/aspose.slides/iautoshape/shape_style/) |  |
| [`shape_type`](/slides/python-net/pt/aspose.slides/iautoshape/shape_type/) |  |
| [`adjustments`](/slides/python-net/pt/aspose.slides/iautoshape/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/pt/aspose.slides/iautoshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/pt/aspose.slides/iautoshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/pt/aspose.slides/iautoshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/pt/aspose.slides/iautoshape/raw_frame/) |  |
| [`frame`](/slides/python-net/pt/aspose.slides/iautoshape/frame/) |  |
| [`line_format`](/slides/python-net/pt/aspose.slides/iautoshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/pt/aspose.slides/iautoshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/pt/aspose.slides/iautoshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/pt/aspose.slides/iautoshape/fill_format/) |  |
| [`hidden`](/slides/python-net/pt/aspose.slides/iautoshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/pt/aspose.slides/iautoshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/pt/aspose.slides/iautoshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/pt/aspose.slides/iautoshape/rotation/) |  |
| [`x`](/slides/python-net/pt/aspose.slides/iautoshape/x/) |  |
| [`y`](/slides/python-net/pt/aspose.slides/iautoshape/y/) |  |
| [`width`](/slides/python-net/pt/aspose.slides/iautoshape/width/) |  |
| [`height`](/slides/python-net/pt/aspose.slides/iautoshape/height/) |  |
| [`alternative_text`](/slides/python-net/pt/aspose.slides/iautoshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/pt/aspose.slides/iautoshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/pt/aspose.slides/iautoshape/name/) |  |
| [`is_decorative`](/slides/python-net/pt/aspose.slides/iautoshape/is_decorative/) |  |
| [`unique_id`](/slides/python-net/pt/aspose.slides/iautoshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/pt/aspose.slides/iautoshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/pt/aspose.slides/iautoshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/pt/aspose.slides/iautoshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/pt/aspose.slides/iautoshape/parent_group/) |  |
| [`slide`](/slides/python-net/pt/aspose.slides/iautoshape/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides/iautoshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/pt/aspose.slides/iautoshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/pt/aspose.slides/iautoshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/pt/aspose.slides/iautoshape/hyperlink_manager/) |  |

## Métodos

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pt/aspose.slides/iautoshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pt/aspose.slides/iautoshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/pt/aspose.slides/iautoshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pt/aspose.slides/iautoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`add_text_frame(self, text)`](/slides/python-net/pt/aspose.slides/iautoshape/add_text_frame/#str) | Adiciona um novo TextFrame a uma forma.<br/>            Se a forma já possui TextFrame, então simplesmente altera seu texto. |
| [`get_geometry_paths(self)`](/slides/python-net/pt/aspose.slides/iautoshape/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/pt/aspose.slides/iautoshape/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/pt/aspose.slides/iautoshape/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/pt/aspose.slides/iautoshape/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pt/aspose.slides/iautoshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/pt/aspose.slides/iautoshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/pt/aspose.slides/iautoshape/get_base_placeholder/#) |  |


### Ver também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)