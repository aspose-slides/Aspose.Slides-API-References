---
title: IConnector class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/iconnector/
---
## IConnector classe

Representa um conector.

O tipo IConnector expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`shape_lock`](/slides/python-net/pt/aspose.slides/iconnector/shape_lock/) | Returns shape's locks.<br/>            Somente leitura [`IConnectorLock`](/slides/python-net/pt/aspose.slides/iconnectorlock). |
| [`connector_lock`](/slides/python-net/pt/aspose.slides/iconnector/connector_lock/) | Returns Connector's locks.<br/>            Somente leitura [`IConnectorLock`](/slides/python-net/pt/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/pt/aspose.slides/iconnector/start_shape_connected_to/) | Returns or sets the shape to attach the beginning of the connector to.<br/>            Leitura/gravação [`IShape`](/slides/python-net/pt/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/pt/aspose.slides/iconnector/end_shape_connected_to/) | Returns or sets the shape to attach the end of the connector to.<br/>            Leitura/gravação [`IShape`](/slides/python-net/pt/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/pt/aspose.slides/iconnector/start_shape_connection_site_index/) | Returns or sets the index of connection site for start shape.<br/>            Leitura/gravação **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/pt/aspose.slides/iconnector/end_shape_connection_site_index/) | Returns or sets the index of connection site for end shape.<br/>            Leitura/gravação **int**. |
| [`shape_style`](/slides/python-net/pt/aspose.slides/iconnector/shape_style/) |  |
| [`shape_type`](/slides/python-net/pt/aspose.slides/iconnector/shape_type/) |  |
| [`adjustments`](/slides/python-net/pt/aspose.slides/iconnector/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/pt/aspose.slides/iconnector/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/pt/aspose.slides/iconnector/placeholder/) |  |
| [`custom_data`](/slides/python-net/pt/aspose.slides/iconnector/custom_data/) |  |
| [`raw_frame`](/slides/python-net/pt/aspose.slides/iconnector/raw_frame/) |  |
| [`frame`](/slides/python-net/pt/aspose.slides/iconnector/frame/) |  |
| [`line_format`](/slides/python-net/pt/aspose.slides/iconnector/line_format/) |  |
| [`three_d_format`](/slides/python-net/pt/aspose.slides/iconnector/three_d_format/) |  |
| [`effect_format`](/slides/python-net/pt/aspose.slides/iconnector/effect_format/) |  |
| [`fill_format`](/slides/python-net/pt/aspose.slides/iconnector/fill_format/) |  |
| [`hidden`](/slides/python-net/pt/aspose.slides/iconnector/hidden/) |  |
| [`z_order_position`](/slides/python-net/pt/aspose.slides/iconnector/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/pt/aspose.slides/iconnector/connection_site_count/) |  |
| [`rotation`](/slides/python-net/pt/aspose.slides/iconnector/rotation/) |  |
| [`x`](/slides/python-net/pt/aspose.slides/iconnector/x/) |  |
| [`y`](/slides/python-net/pt/aspose.slides/iconnector/y/) |  |
| [`width`](/slides/python-net/pt/aspose.slides/iconnector/width/) |  |
| [`height`](/slides/python-net/pt/aspose.slides/iconnector/height/) |  |
| [`alternative_text`](/slides/python-net/pt/aspose.slides/iconnector/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/pt/aspose.slides/iconnector/alternative_text_title/) |  |
| [`name`](/slides/python-net/pt/aspose.slides/iconnector/name/) |  |
| [`is_decorative`](/slides/python-net/pt/aspose.slides/iconnector/is_decorative/) |  |
| [`unique_id`](/slides/python-net/pt/aspose.slides/iconnector/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/pt/aspose.slides/iconnector/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/pt/aspose.slides/iconnector/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/pt/aspose.slides/iconnector/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/pt/aspose.slides/iconnector/parent_group/) |  |
| [`slide`](/slides/python-net/pt/aspose.slides/iconnector/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides/iconnector/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/pt/aspose.slides/iconnector/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/pt/aspose.slides/iconnector/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/pt/aspose.slides/iconnector/hyperlink_manager/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pt/aspose.slides/iconnector/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pt/aspose.slides/iconnector/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/pt/aspose.slides/iconnector/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pt/aspose.slides/iconnector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`reroute(self)`](/slides/python-net/pt/aspose.slides/iconnector/reroute/#) | Redireciona o conector para que ele siga o caminho mais curto possível entre as formas que conecta. |
| [`get_geometry_paths(self)`](/slides/python-net/pt/aspose.slides/iconnector/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/pt/aspose.slides/iconnector/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/pt/aspose.slides/iconnector/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/pt/aspose.slides/iconnector/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pt/aspose.slides/iconnector/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/pt/aspose.slides/iconnector/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/pt/aspose.slides/iconnector/get_base_placeholder/#) |  |

### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)