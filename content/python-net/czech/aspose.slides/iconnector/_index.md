---
title: IConnector class
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/iconnector/
---
## IConnector třída

Reprezentuje konektor.

Typ IConnector obsahuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`shape_lock`](/slides/python-net/cs/aspose.slides/iconnector/shape_lock/) | Vrací zámky tvaru.<br/>            Pouze ke čtení [`IConnectorLock`](/slides/python-net/cs/aspose.slides/iconnectorlock). |
| [`connector_lock`](/slides/python-net/cs/aspose.slides/iconnector/connector_lock/) | Vrací zámky konektoru.<br/>            Pouze ke čtení [`IConnectorLock`](/slides/python-net/cs/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/cs/aspose.slides/iconnector/start_shape_connected_to/) | Vrací nebo nastavuje tvar, ke kterému se připojuje začátek konektoru.<br/>            Čtení/Zápis [`IShape`](/slides/python-net/cs/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/cs/aspose.slides/iconnector/end_shape_connected_to/) | Vrací nebo nastavuje tvar, ke kterému se připojuje konec konektoru.<br/>            Čtení/Zápis [`IShape`](/slides/python-net/cs/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/cs/aspose.slides/iconnector/start_shape_connection_site_index/) | Vrací nebo nastavuje index připojovacího místa pro počáteční tvar.<br/>            Čtení/Zápis **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/cs/aspose.slides/iconnector/end_shape_connection_site_index/) | Vrací nebo nastavuje index připojovacího místa pro koncový tvar.<br/>            Čtení/Zápis **int**. |
| [`shape_style`](/slides/python-net/cs/aspose.slides/iconnector/shape_style/) |  |
| [`shape_type`](/slides/python-net/cs/aspose.slides/iconnector/shape_type/) |  |
| [`adjustments`](/slides/python-net/cs/aspose.slides/iconnector/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/cs/aspose.slides/iconnector/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/cs/aspose.slides/iconnector/placeholder/) |  |
| [`custom_data`](/slides/python-net/cs/aspose.slides/iconnector/custom_data/) |  |
| [`raw_frame`](/slides/python-net/cs/aspose.slides/iconnector/raw_frame/) |  |
| [`frame`](/slides/python-net/cs/aspose.slides/iconnector/frame/) |  |
| [`line_format`](/slides/python-net/cs/aspose.slides/iconnector/line_format/) |  |
| [`three_d_format`](/slides/python-net/cs/aspose.slides/iconnector/three_d_format/) |  |
| [`effect_format`](/slides/python-net/cs/aspose.slides/iconnector/effect_format/) |  |
| [`fill_format`](/slides/python-net/cs/aspose.slides/iconnector/fill_format/) |  |
| [`hidden`](/slides/python-net/cs/aspose.slides/iconnector/hidden/) |  |
| [`z_order_position`](/slides/python-net/cs/aspose.slides/iconnector/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/cs/aspose.slides/iconnector/connection_site_count/) |  |
| [`rotation`](/slides/python-net/cs/aspose.slides/iconnector/rotation/) |  |
| [`x`](/slides/python-net/cs/aspose.slides/iconnector/x/) |  |
| [`y`](/slides/python-net/cs/aspose.slides/iconnector/y/) |  |
| [`width`](/slides/python-net/cs/aspose.slides/iconnector/width/) |  |
| [`height`](/slides/python-net/cs/aspose.slides/iconnector/height/) |  |
| [`alternative_text`](/slides/python-net/cs/aspose.slides/iconnector/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/cs/aspose.slides/iconnector/alternative_text_title/) |  |
| [`name`](/slides/python-net/cs/aspose.slides/iconnector/name/) |  |
| [`is_decorative`](/slides/python-net/cs/aspose.slides/iconnector/is_decorative/) |  |
| [`unique_id`](/slides/python-net/cs/aspose.slides/iconnector/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/cs/aspose.slides/iconnector/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/cs/aspose.slides/iconnector/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/cs/aspose.slides/iconnector/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/cs/aspose.slides/iconnector/parent_group/) |  |
| [`slide`](/slides/python-net/cs/aspose.slides/iconnector/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides/iconnector/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/cs/aspose.slides/iconnector/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/cs/aspose.slides/iconnector/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/cs/aspose.slides/iconnector/hyperlink_manager/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/cs/aspose.slides/iconnector/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/iconnector/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/cs/aspose.slides/iconnector/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/cs/aspose.slides/iconnector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`reroute(self)`](/slides/python-net/cs/aspose.slides/iconnector/reroute/#) | Přesměruje konektor tak, aby zvolil nejkratší možnou cestu mezi tvary, které spojuje. |
| [`get_geometry_paths(self)`](/slides/python-net/cs/aspose.slides/iconnector/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/cs/aspose.slides/iconnector/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/cs/aspose.slides/iconnector/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/cs/aspose.slides/iconnector/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/cs/aspose.slides/iconnector/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/cs/aspose.slides/iconnector/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/cs/aspose.slides/iconnector/get_base_placeholder/#) |  |

### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)