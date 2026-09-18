---
title: IGeometryShape class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/igeometryshape/
---
## IGeometryShape classe

Representa a classe base para todas as formas geométricas.

O tipo IGeometryShape expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`shape_style`](/slides/python-net/pt/aspose.slides/igeometryshape/shape_style/) | Retorna o objeto de estilo da forma.<br/>            Somente leitura [`IShapeStyle`](/slides/python-net/pt/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/pt/aspose.slides/igeometryshape/shape_type/) | Retorna ou define o tipo predefinido de geometria.<br/>            Nota: ao alterar o valor, todos os valores de ajuste serão redefinidos para seus valores padrão.<br/>            Leitura/gravação [`ShapeType`](/slides/python-net/pt/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/pt/aspose.slides/igeometryshape/adjustments/) | Retorna uma coleção dos valores de ajuste da forma.<br/>            Somente leitura [`IAdjustValueCollection`](/slides/python-net/pt/aspose.slides/iadjustvaluecollection). |
| [`is_text_holder`](/slides/python-net/pt/aspose.slides/igeometryshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/pt/aspose.slides/igeometryshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/pt/aspose.slides/igeometryshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/pt/aspose.slides/igeometryshape/raw_frame/) |  |
| [`frame`](/slides/python-net/pt/aspose.slides/igeometryshape/frame/) |  |
| [`line_format`](/slides/python-net/pt/aspose.slides/igeometryshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/pt/aspose.slides/igeometryshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/pt/aspose.slides/igeometryshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/pt/aspose.slides/igeometryshape/fill_format/) |  |
| [`hidden`](/slides/python-net/pt/aspose.slides/igeometryshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/pt/aspose.slides/igeometryshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/pt/aspose.slides/igeometryshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/pt/aspose.slides/igeometryshape/rotation/) |  |
| [`x`](/slides/python-net/pt/aspose.slides/igeometryshape/x/) |  |
| [`y`](/slides/python-net/pt/aspose.slides/igeometryshape/y/) |  |
| [`width`](/slides/python-net/pt/aspose.slides/igeometryshape/width/) |  |
| [`height`](/slides/python-net/pt/aspose.slides/igeometryshape/height/) |  |
| [`alternative_text`](/slides/python-net/pt/aspose.slides/igeometryshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/pt/aspose.slides/igeometryshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/pt/aspose.slides/igeometryshape/name/) |  |
| [`is_decorative`](/slides/python-net/pt/aspose.slides/igeometryshape/is_decorative/) |  |
| [`shape_lock`](/slides/python-net/pt/aspose.slides/igeometryshape/shape_lock/) |  |
| [`unique_id`](/slides/python-net/pt/aspose.slides/igeometryshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/pt/aspose.slides/igeometryshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/pt/aspose.slides/igeometryshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/pt/aspose.slides/igeometryshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/pt/aspose.slides/igeometryshape/parent_group/) |  |
| [`slide`](/slides/python-net/pt/aspose.slides/igeometryshape/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides/igeometryshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/pt/aspose.slides/igeometryshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/pt/aspose.slides/igeometryshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/pt/aspose.slides/igeometryshape/hyperlink_manager/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pt/aspose.slides/igeometryshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pt/aspose.slides/igeometryshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/pt/aspose.slides/igeometryshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pt/aspose.slides/igeometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/pt/aspose.slides/igeometryshape/get_geometry_paths/#) | Retorna a cópia do caminho da forma geométrica. As coordenadas são relativas ao canto superior esquerdo da forma. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/pt/aspose.slides/igeometryshape/set_geometry_path/#igeometrypath) | Atualiza a geometria da forma a partir do objeto [`IGeometryPath`](/slides/python-net/pt/aspose.slides/igeometrypath). As coordenadas devem ser relativas ao canto superior esquerdo da forma.<br/>             Altera o tipo da forma ([`IGeometryShape.shape_type`](/slides/python-net/pt/aspose.slides/igeometryshape/shape_type)) para [`ShapeType.CUSTOM`](/slides/python-net/pt/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/pt/aspose.slides/igeometryshape/set_geometry_paths/#listigeometrypath) | Atualiza a geometria da forma a partir de um array de [`IGeometryPath`](/slides/python-net/pt/aspose.slides/igeometrypath). As coordenadas devem ser relativas ao canto superior esquerdo da forma.<br/>             Altera o tipo da forma ([`IGeometryShape.shape_type`](/slides/python-net/pt/aspose.slides/igeometryshape/shape_type)) para [`ShapeType.CUSTOM`](/slides/python-net/pt/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/pt/aspose.slides/igeometryshape/create_shape_elements/#) | Cria e retorna um array dos elementos da forma. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pt/aspose.slides/igeometryshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/pt/aspose.slides/igeometryshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/pt/aspose.slides/igeometryshape/get_base_placeholder/#) |  |

### Ver Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)