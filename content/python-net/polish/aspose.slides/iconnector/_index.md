---
title: IConnector class
second_title: Aspose.Slides dla Pythona przez .NET API Reference
description: 
type: docs
url: /pl/aspose.slides/iconnector/
---
## IConnector klasa

Reprezentuje łącznik.

Typ IConnector udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`shape_lock`](/slides/python-net/pl/aspose.slides/iconnector/shape_lock/) | Zwraca blokady kształtu.<br/>            Tylko do odczytu [`IConnectorLock`](/slides/python-net/pl/aspose.slides/iconnectorlock). |
| [`connector_lock`](/slides/python-net/pl/aspose.slides/iconnector/connector_lock/) | Zwraca blokady łącza.<br/>            Tylko do odczytu [`IConnectorLock`](/slides/python-net/pl/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/pl/aspose.slides/iconnector/start_shape_connected_to/) | Zwraca lub ustawia kształt, do którego podłączany jest początek łącznika.<br/>            Odczyt/zapis [`IShape`](/slides/python-net/pl/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/pl/aspose.slides/iconnector/end_shape_connected_to/) | Zwraca lub ustawia kształt, do którego podłączany jest koniec łącznika.<br/>            Odczyt/zapis [`IShape`](/slides/python-net/pl/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/pl/aspose.slides/iconnector/start_shape_connection_site_index/) | Zwraca lub ustawia indeks miejsca połączenia dla kształtu początkowego.<br/>            Odczyt/zapis **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/pl/aspose.slides/iconnector/end_shape_connection_site_index/) | Zwraca lub ustawia indeks miejsca połączenia dla kształtu końcowego.<br/>            Odczyt/zapis **int**. |
| [`shape_style`](/slides/python-net/pl/aspose.slides/iconnector/shape_style/) |  |
| [`shape_type`](/slides/python-net/pl/aspose.slides/iconnector/shape_type/) |  |
| [`adjustments`](/slides/python-net/pl/aspose.slides/iconnector/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/pl/aspose.slides/iconnector/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/pl/aspose.slides/iconnector/placeholder/) |  |
| [`custom_data`](/slides/python-net/pl/aspose.slides/iconnector/custom_data/) |  |
| [`raw_frame`](/slides/python-net/pl/aspose.slides/iconnector/raw_frame/) |  |
| [`frame`](/slides/python-net/pl/aspose.slides/iconnector/frame/) |  |
| [`line_format`](/slides/python-net/pl/aspose.slides/iconnector/line_format/) |  |
| [`three_d_format`](/slides/python-net/pl/aspose.slides/iconnector/three_d_format/) |  |
| [`effect_format`](/slides/python-net/pl/aspose.slides/iconnector/effect_format/) |  |
| [`fill_format`](/slides/python-net/pl/aspose.slides/iconnector/fill_format/) |  |
| [`hidden`](/slides/python-net/pl/aspose.slides/iconnector/hidden/) |  |
| [`z_order_position`](/slides/python-net/pl/aspose.slides/iconnector/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/pl/aspose.slides/iconnector/connection_site_count/) |  |
| [`rotation`](/slides/python-net/pl/aspose.slides/iconnector/rotation/) |  |
| [`x`](/slides/python-net/pl/aspose.slides/iconnector/x/) |  |
| [`y`](/slides/python-net/pl/aspose.slides/iconnector/y/) |  |
| [`width`](/slides/python-net/pl/aspose.slides/iconnector/width/) |  |
| [`height`](/slides/python-net/pl/aspose.slides/iconnector/height/) |  |
| [`alternative_text`](/slides/python-net/pl/aspose.slides/iconnector/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/pl/aspose.slides/iconnector/alternative_text_title/) |  |
| [`name`](/slides/python-net/pl/aspose.slides/iconnector/name/) |  |
| [`is_decorative`](/slides/python-net/pl/aspose.slides/iconnector/is_decorative/) |  |
| [`unique_id`](/slides/python-net/pl/aspose.slides/iconnector/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/pl/aspose.slides/iconnector/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/pl/aspose.slides/iconnector/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/pl/aspose.slides/iconnector/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/pl/aspose.slides/iconnector/parent_group/) |  |
| [`slide`](/slides/python-net/pl/aspose.slides/iconnector/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides/iconnector/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/pl/aspose.slides/iconnector/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/pl/aspose.slides/iconnector/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/pl/aspose.slides/iconnector/hyperlink_manager/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pl/aspose.slides/iconnector/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pl/aspose.slides/iconnector/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/pl/aspose.slides/iconnector/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pl/aspose.slides/iconnector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`reroute(self)`](/slides/python-net/pl/aspose.slides/iconnector/reroute/#) | Przekierowuje łącznik, tak aby przyjął najkrótszą możliwą ścieżkę pomiędzy kształtami, które łączy. |
| [`get_geometry_paths(self)`](/slides/python-net/pl/aspose.slides/iconnector/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/pl/aspose.slides/iconnector/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/pl/aspose.slides/iconnector/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/pl/aspose.slides/iconnector/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pl/aspose.slides/iconnector/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/pl/aspose.slides/iconnector/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/pl/aspose.slides/iconnector/get_base_placeholder/#) |  |


### Zobacz również
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)