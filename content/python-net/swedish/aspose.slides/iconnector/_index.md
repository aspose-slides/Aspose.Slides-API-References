---
title: IConnector class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/iconnector/
---
## IConnector klass

Representerar en anslutare.

IConnector-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`shape_lock`](/slides/python-net/sv/aspose.slides/iconnector/shape_lock/) | Returnerar lås för formen.<br/>            Endast läsning [`IConnectorLock`](/slides/python-net/sv/aspose.slides/iconnectorlock). |
| [`connector_lock`](/slides/python-net/sv/aspose.slides/iconnector/connector_lock/) | Returnerar lås för anslutaren.<br/>            Endast läsning [`IConnectorLock`](/slides/python-net/sv/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/sv/aspose.slides/iconnector/start_shape_connected_to/) | Returnerar eller anger formen som början av anslutaren ska fästas vid.<br/>            Läs/skriv [`IShape`](/slides/python-net/sv/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/sv/aspose.slides/iconnector/end_shape_connected_to/) | Returnerar eller anger formen som slutet av anslutaren ska fästas vid.<br/>            Läs/skriv [`IShape`](/slides/python-net/sv/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/sv/aspose.slides/iconnector/start_shape_connection_site_index/) | Returnerar eller anger index för anslutningsplats för startformen.<br/>            Läs/skriv **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/sv/aspose.slides/iconnector/end_shape_connection_site_index/) | Returnerar eller anger index för anslutningsplats för slutformen.<br/>            Läs/skriv **int**. |
| [`shape_style`](/slides/python-net/sv/aspose.slides/iconnector/shape_style/) |  |
| [`shape_type`](/slides/python-net/sv/aspose.slides/iconnector/shape_type/) |  |
| [`adjustments`](/slides/python-net/sv/aspose.slides/iconnector/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/sv/aspose.slides/iconnector/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/sv/aspose.slides/iconnector/placeholder/) |  |
| [`custom_data`](/slides/python-net/sv/aspose.slides/iconnector/custom_data/) |  |
| [`raw_frame`](/slides/python-net/sv/aspose.slides/iconnector/raw_frame/) |  |
| [`frame`](/slides/python-net/sv/aspose.slides/iconnector/frame/) |  |
| [`line_format`](/slides/python-net/sv/aspose.slides/iconnector/line_format/) |  |
| [`three_d_format`](/slides/python-net/sv/aspose.slides/iconnector/three_d_format/) |  |
| [`effect_format`](/slides/python-net/sv/aspose.slides/iconnector/effect_format/) |  |
| [`fill_format`](/slides/python-net/sv/aspose.slides/iconnector/fill_format/) |  |
| [`hidden`](/slides/python-net/sv/aspose.slides/iconnector/hidden/) |  |
| [`z_order_position`](/slides/python-net/sv/aspose.slides/iconnector/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/sv/aspose.slides/iconnector/connection_site_count/) |  |
| [`rotation`](/slides/python-net/sv/aspose.slides/iconnector/rotation/) |  |
| [`x`](/slides/python-net/sv/aspose.slides/iconnector/x/) |  |
| [`y`](/slides/python-net/sv/aspose.slides/iconnector/y/) |  |
| [`width`](/slides/python-net/sv/aspose.slides/iconnector/width/) |  |
| [`height`](/slides/python-net/sv/aspose.slides/iconnector/height/) |  |
| [`alternative_text`](/slides/python-net/sv/aspose.slides/iconnector/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/sv/aspose.slides/iconnector/alternative_text_title/) |  |
| [`name`](/slides/python-net/sv/aspose.slides/iconnector/name/) |  |
| [`is_decorative`](/slides/python-net/sv/aspose.slides/iconnector/is_decorative/) |  |
| [`unique_id`](/slides/python-net/sv/aspose.slides/iconnector/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/sv/aspose.slides/iconnector/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/sv/aspose.slides/iconnector/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/sv/aspose.slides/iconnector/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/sv/aspose.slides/iconnector/parent_group/) |  |
| [`slide`](/slides/python-net/sv/aspose.slides/iconnector/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides/iconnector/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/sv/aspose.slides/iconnector/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/sv/aspose.slides/iconnector/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/sv/aspose.slides/iconnector/hyperlink_manager/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_image(self)`](/slides/python-net/sv/aspose.slides/iconnector/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides/iconnector/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/sv/aspose.slides/iconnector/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/sv/aspose.slides/iconnector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`reroute(self)`](/slides/python-net/sv/aspose.slides/iconnector/reroute/#) | Omruttar anslutaren så att den tar den kortaste möjliga vägen mellan formerna den ansluter. |
| [`get_geometry_paths(self)`](/slides/python-net/sv/aspose.slides/iconnector/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/sv/aspose.slides/iconnector/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/sv/aspose.slides/iconnector/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/sv/aspose.slides/iconnector/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/sv/aspose.slides/iconnector/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/sv/aspose.slides/iconnector/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/sv/aspose.slides/iconnector/get_base_placeholder/#) |  |

### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)