---
title: IConnector class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/iconnector/
---
## IConnector clase

Representa un conector.

El tipo IConnector expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`shape_lock`](/slides/python-net/es/aspose.slides/iconnector/shape_lock/) | Devuelve los bloqueos de la forma.<br/>            Solo lectura [`IConnectorLock`](/slides/python-net/es/aspose.slides/iconnectorlock). |
| [`connector_lock`](/slides/python-net/es/aspose.slides/iconnector/connector_lock/) | Devuelve los bloqueos del conector.<br/>            Solo lectura [`IConnectorLock`](/slides/python-net/es/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/es/aspose.slides/iconnector/start_shape_connected_to/) | Devuelve o establece la forma a la que se debe adjuntar el inicio del conector.<br/>            Lectura/escritura [`IShape`](/slides/python-net/es/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/es/aspose.slides/iconnector/end_shape_connected_to/) | Devuelve o establece la forma a la que se debe adjuntar el final del conector.<br/>            Lectura/escritura [`IShape`](/slides/python-net/es/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/es/aspose.slides/iconnector/start_shape_connection_site_index/) | Devuelve o establece el índice del punto de conexión para la forma inicial.<br/>            Lectura/escritura **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/es/aspose.slides/iconnector/end_shape_connection_site_index/) | Devuelve o establece el índice del punto de conexión para la forma final.<br/>            Lectura/escritura **int**. |
| [`shape_style`](/slides/python-net/es/aspose.slides/iconnector/shape_style/) |  |
| [`shape_type`](/slides/python-net/es/aspose.slides/iconnector/shape_type/) |  |
| [`adjustments`](/slides/python-net/es/aspose.slides/iconnector/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/es/aspose.slides/iconnector/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/es/aspose.slides/iconnector/placeholder/) |  |
| [`custom_data`](/slides/python-net/es/aspose.slides/iconnector/custom_data/) |  |
| [`raw_frame`](/slides/python-net/es/aspose.slides/iconnector/raw_frame/) |  |
| [`frame`](/slides/python-net/es/aspose.slides/iconnector/frame/) |  |
| [`line_format`](/slides/python-net/es/aspose.slides/iconnector/line_format/) |  |
| [`three_d_format`](/slides/python-net/es/aspose.slides/iconnector/three_d_format/) |  |
| [`effect_format`](/slides/python-net/es/aspose.slides/iconnector/effect_format/) |  |
| [`fill_format`](/slides/python-net/es/aspose.slides/iconnector/fill_format/) |  |
| [`hidden`](/slides/python-net/es/aspose.slides/iconnector/hidden/) |  |
| [`z_order_position`](/slides/python-net/es/aspose.slides/iconnector/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/es/aspose.slides/iconnector/connection_site_count/) |  |
| [`rotation`](/slides/python-net/es/aspose.slides/iconnector/rotation/) |  |
| [`x`](/slides/python-net/es/aspose.slides/iconnector/x/) |  |
| [`y`](/slides/python-net/es/aspose.slides/iconnector/y/) |  |
| [`width`](/slides/python-net/es/aspose.slides/iconnector/width/) |  |
| [`height`](/slides/python-net/es/aspose.slides/iconnector/height/) |  |
| [`alternative_text`](/slides/python-net/es/aspose.slides/iconnector/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/es/aspose.slides/iconnector/alternative_text_title/) |  |
| [`name`](/slides/python-net/es/aspose.slides/iconnector/name/) |  |
| [`is_decorative`](/slides/python-net/es/aspose.slides/iconnector/is_decorative/) |  |
| [`unique_id`](/slides/python-net/es/aspose.slides/iconnector/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/es/aspose.slides/iconnector/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/es/aspose.slides/iconnector/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/es/aspose.slides/iconnector/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/es/aspose.slides/iconnector/parent_group/) |  |
| [`slide`](/slides/python-net/es/aspose.slides/iconnector/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides/iconnector/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/es/aspose.slides/iconnector/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/es/aspose.slides/iconnector/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/es/aspose.slides/iconnector/hyperlink_manager/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`get_image(self)`](/slides/python-net/es/aspose.slides/iconnector/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/es/aspose.slides/iconnector/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/es/aspose.slides/iconnector/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/es/aspose.slides/iconnector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`reroute(self)`](/slides/python-net/es/aspose.slides/iconnector/reroute/#) | Redirige el conector para que tome la ruta más corta posible entre las formas que conecta. |
| [`get_geometry_paths(self)`](/slides/python-net/es/aspose.slides/iconnector/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/es/aspose.slides/iconnector/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/es/aspose.slides/iconnector/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/es/aspose.slides/iconnector/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/es/aspose.slides/iconnector/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/es/aspose.slides/iconnector/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/es/aspose.slides/iconnector/get_base_placeholder/#) |  |

### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)