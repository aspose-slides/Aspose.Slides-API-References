---
title: IConnector class
second_title: Aspose.Slides for Python .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/iconnector/
---
## IConnector osztály

Az IConnector típusa a következő tagokat teszi közzé:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`shape_lock`](/slides/python-net/hu/aspose.slides/iconnector/shape_lock/) | Visszaadja az alakzat zárait.<br/>            Csak olvasható [`IConnectorLock`](/slides/python-net/hu/aspose.slides/iconnectorlock). |
| [`connector_lock`](/slides/python-net/hu/aspose.slides/iconnector/connector_lock/) | Visszaadja a Connector zárait.<br/>            Csak olvasható [`IConnectorLock`](/slides/python-net/hu/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/hu/aspose.slides/iconnector/start_shape_connected_to/) | Visszaadja vagy beállítja azt az alakzatot, amelyhez a connector kezdete csatlakozik.<br/>            Olvasás/írás [`IShape`](/slides/python-net/hu/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/hu/aspose.slides/iconnector/end_shape_connected_to/) | Visszaadja vagy beállítja azt az alakzatot, amelyhez a connector vége csatlakozik.<br/>            Olvasás/írás [`IShape`](/slides/python-net/hu/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/hu/aspose.slides/iconnector/start_shape_connection_site_index/) | Visszaadja vagy beállítja a kezdő alakzat csatlakozási helyének indexét.<br/>            Olvasás/írás **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/hu/aspose.slides/iconnector/end_shape_connection_site_index/) | Visszaadja vagy beállítja a befejező alakzat csatlakozási helyének indexét.<br/>            Olvasás/írás **int**. |
| [`shape_style`](/slides/python-net/hu/aspose.slides/iconnector/shape_style/) |  |
| [`shape_type`](/slides/python-net/hu/aspose.slides/iconnector/shape_type/) |  |
| [`adjustments`](/slides/python-net/hu/aspose.slides/iconnector/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/hu/aspose.slides/iconnector/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/hu/aspose.slides/iconnector/placeholder/) |  |
| [`custom_data`](/slides/python-net/hu/aspose.slides/iconnector/custom_data/) |  |
| [`raw_frame`](/slides/python-net/hu/aspose.slides/iconnector/raw_frame/) |  |
| [`frame`](/slides/python-net/hu/aspose.slides/iconnector/frame/) |  |
| [`line_format`](/slides/python-net/hu/aspose.slides/iconnector/line_format/) |  |
| [`three_d_format`](/slides/python-net/hu/aspose.slides/iconnector/three_d_format/) |  |
| [`effect_format`](/slides/python-net/hu/aspose.slides/iconnector/effect_format/) |  |
| [`fill_format`](/slides/python-net/hu/aspose.slides/iconnector/fill_format/) |  |
| [`hidden`](/slides/python-net/hu/aspose.slides/iconnector/hidden/) |  |
| [`z_order_position`](/slides/python-net/hu/aspose.slides/iconnector/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/hu/aspose.slides/iconnector/connection_site_count/) |  |
| [`rotation`](/slides/python-net/hu/aspose.slides/iconnector/rotation/) |  |
| [`x`](/slides/python-net/hu/aspose.slides/iconnector/x/) |  |
| [`y`](/slides/python-net/hu/aspose.slides/iconnector/y/) |  |
| [`width`](/slides/python-net/hu/aspose.slides/iconnector/width/) |  |
| [`height`](/slides/python-net/hu/aspose.slides/iconnector/height/) |  |
| [`alternative_text`](/slides/python-net/hu/aspose.slides/iconnector/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/hu/aspose.slides/iconnector/alternative_text_title/) |  |
| [`name`](/slides/python-net/hu/aspose.slides/iconnector/name/) |  |
| [`is_decorative`](/slides/python-net/hu/aspose.slides/iconnector/is_decorative/) |  |
| [`unique_id`](/slides/python-net/hu/aspose.slides/iconnector/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/hu/aspose.slides/iconnector/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/hu/aspose.slides/iconnector/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/hu/aspose.slides/iconnector/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/hu/aspose.slides/iconnector/parent_group/) |  |
| [`slide`](/slides/python-net/hu/aspose.slides/iconnector/slide/) |  |
| [`presentation`](/slides/python-net/hu/aspose.slides/iconnector/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/hu/aspose.slides/iconnector/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/hu/aspose.slides/iconnector/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/hu/aspose.slides/iconnector/hyperlink_manager/) |  |

## Metódusok

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hu/aspose.slides/iconnector/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/iconnector/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/hu/aspose.slides/iconnector/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hu/aspose.slides/iconnector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`reroute(self)`](/slides/python-net/hu/aspose.slides/iconnector/reroute/#) | Újratervezi a kapcsolatot, hogy a csatlakoztatott alakzatok között a legrövidebb lehetséges útvonalat vegye. |
| [`get_geometry_paths(self)`](/slides/python-net/hu/aspose.slides/iconnector/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/hu/aspose.slides/iconnector/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/hu/aspose.slides/iconnector/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/hu/aspose.slides/iconnector/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hu/aspose.slides/iconnector/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/hu/aspose.slides/iconnector/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/hu/aspose.slides/iconnector/get_base_placeholder/#) |  |


### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)