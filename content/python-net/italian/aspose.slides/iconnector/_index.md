---
title: IConnector class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/iconnector/
---
## IConnector classe

Rappresenta un connettore.

Il tipo IConnector espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`shape_lock`](/slides/python-net/it/aspose.slides/iconnector/shape_lock/) | Restituisce i blocchi della forma.<br/>            Sola lettura [`IConnectorLock`](/slides/python-net/it/aspose.slides/iconnectorlock). |
| [`connector_lock`](/slides/python-net/it/aspose.slides/iconnector/connector_lock/) | Restituisce i blocchi del connettore.<br/>            Sola lettura [`IConnectorLock`](/slides/python-net/it/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/it/aspose.slides/iconnector/start_shape_connected_to/) | Restituisce o imposta la forma a cui collegare l'inizio del connettore.<br/>            Lettura/scrittura [`IShape`](/slides/python-net/it/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/it/aspose.slides/iconnector/end_shape_connected_to/) | Restituisce o imposta la forma a cui collegare la fine del connettore.<br/>            Lettura/scrittura [`IShape`](/slides/python-net/it/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/it/aspose.slides/iconnector/start_shape_connection_site_index/) | Restituisce o imposta l'indice del punto di connessione per la forma iniziale.<br/>            Lettura/scrittura **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/it/aspose.slides/iconnector/end_shape_connection_site_index/) | Restituisce o imposta l'indice del punto di connessione per la forma finale.<br/>            Lettura/scrittura **int**. |
| [`shape_style`](/slides/python-net/it/aspose.slides/iconnector/shape_style/) |  |
| [`shape_type`](/slides/python-net/it/aspose.slides/iconnector/shape_type/) |  |
| [`adjustments`](/slides/python-net/it/aspose.slides/iconnector/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/it/aspose.slides/iconnector/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/it/aspose.slides/iconnector/placeholder/) |  |
| [`custom_data`](/slides/python-net/it/aspose.slides/iconnector/custom_data/) |  |
| [`raw_frame`](/slides/python-net/it/aspose.slides/iconnector/raw_frame/) |  |
| [`frame`](/slides/python-net/it/aspose.slides/iconnector/frame/) |  |
| [`line_format`](/slides/python-net/it/aspose.slides/iconnector/line_format/) |  |
| [`three_d_format`](/slides/python-net/it/aspose.slides/iconnector/three_d_format/) |  |
| [`effect_format`](/slides/python-net/it/aspose.slides/iconnector/effect_format/) |  |
| [`fill_format`](/slides/python-net/it/aspose.slides/iconnector/fill_format/) |  |
| [`hidden`](/slides/python-net/it/aspose.slides/iconnector/hidden/) |  |
| [`z_order_position`](/slides/python-net/it/aspose.slides/iconnector/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/it/aspose.slides/iconnector/connection_site_count/) |  |
| [`rotation`](/slides/python-net/it/aspose.slides/iconnector/rotation/) |  |
| [`x`](/slides/python-net/it/aspose.slides/iconnector/x/) |  |
| [`y`](/slides/python-net/it/aspose.slides/iconnector/y/) |  |
| [`width`](/slides/python-net/it/aspose.slides/iconnector/width/) |  |
| [`height`](/slides/python-net/it/aspose.slides/iconnector/height/) |  |
| [`alternative_text`](/slides/python-net/it/aspose.slides/iconnector/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/it/aspose.slides/iconnector/alternative_text_title/) |  |
| [`name`](/slides/python-net/it/aspose.slides/iconnector/name/) |  |
| [`is_decorative`](/slides/python-net/it/aspose.slides/iconnector/is_decorative/) |  |
| [`unique_id`](/slides/python-net/it/aspose.slides/iconnector/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/it/aspose.slides/iconnector/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/it/aspose.slides/iconnector/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/it/aspose.slides/iconnector/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/it/aspose.slides/iconnector/parent_group/) |  |
| [`slide`](/slides/python-net/it/aspose.slides/iconnector/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides/iconnector/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/it/aspose.slides/iconnector/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/it/aspose.slides/iconnector/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/it/aspose.slides/iconnector/hyperlink_manager/) |  |

## Metodi

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/it/aspose.slides/iconnector/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/it/aspose.slides/iconnector/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/it/aspose.slides/iconnector/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/it/aspose.slides/iconnector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`reroute(self)`](/slides/python-net/it/aspose.slides/iconnector/reroute/#) | Riorienta il connettore affinché segua il percorso più breve possibile tra le forme che collega. |
| [`get_geometry_paths(self)`](/slides/python-net/it/aspose.slides/iconnector/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/it/aspose.slides/iconnector/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/it/aspose.slides/iconnector/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/it/aspose.slides/iconnector/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/it/aspose.slides/iconnector/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/it/aspose.slides/iconnector/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/it/aspose.slides/iconnector/get_base_placeholder/#) |  |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)