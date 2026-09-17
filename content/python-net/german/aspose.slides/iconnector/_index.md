---
title: IConnector class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/iconnector/
---
## IConnector Klasse

Stellt einen Connector dar.

Der IConnector-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`shape_lock`](/slides/python-net/de/aspose.slides/iconnector/shape_lock/) | Gibt die Sperren der Form zurück.<br/>            Schreibgeschützt [`IConnectorLock`](/slides/python-net/de/aspose.slides/iconnectorlock). |
| [`connector_lock`](/slides/python-net/de/aspose.slides/iconnector/connector_lock/) | Gibt die Sperren des Connectors zurück.<br/>            Schreibgeschützt [`IConnectorLock`](/slides/python-net/de/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/de/aspose.slides/iconnector/start_shape_connected_to/) | Gibt die Form zurück, an die der Anfang des Connectors angehängt wird, oder legt sie fest.<br/>            Lesen/Schreiben [`IShape`](/slides/python-net/de/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/de/aspose.slides/iconnector/end_shape_connected_to/) | Gibt die Form zurück, an die das Ende des Connectors angehängt wird, oder legt sie fest.<br/>            Lesen/Schreiben [`IShape`](/slides/python-net/de/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/de/aspose.slides/iconnector/start_shape_connection_site_index/) | Gibt den Index der Verbindungsstelle für die Startform zurück oder legt ihn fest.<br/>            Lesen/Schreiben **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/de/aspose.slides/iconnector/end_shape_connection_site_index/) | Gibt den Index der Verbindungsstelle für die Endform zurück oder legt ihn fest.<br/>            Lesen/Schreiben **int**. |
| [`shape_style`](/slides/python-net/de/aspose.slides/iconnector/shape_style/) |  |
| [`shape_type`](/slides/python-net/de/aspose.slides/iconnector/shape_type/) |  |
| [`adjustments`](/slides/python-net/de/aspose.slides/iconnector/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/de/aspose.slides/iconnector/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/de/aspose.slides/iconnector/placeholder/) |  |
| [`custom_data`](/slides/python-net/de/aspose.slides/iconnector/custom_data/) |  |
| [`raw_frame`](/slides/python-net/de/aspose.slides/iconnector/raw_frame/) |  |
| [`frame`](/slides/python-net/de/aspose.slides/iconnector/frame/) |  |
| [`line_format`](/slides/python-net/de/aspose.slides/iconnector/line_format/) |  |
| [`three_d_format`](/slides/python-net/de/aspose.slides/iconnector/three_d_format/) |  |
| [`effect_format`](/slides/python-net/de/aspose.slides/iconnector/effect_format/) |  |
| [`fill_format`](/slides/python-net/de/aspose.slides/iconnector/fill_format/) |  |
| [`hidden`](/slides/python-net/de/aspose.slides/iconnector/hidden/) |  |
| [`z_order_position`](/slides/python-net/de/aspose.slides/iconnector/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/de/aspose.slides/iconnector/connection_site_count/) |  |
| [`rotation`](/slides/python-net/de/aspose.slides/iconnector/rotation/) |  |
| [`x`](/slides/python-net/de/aspose.slides/iconnector/x/) |  |
| [`y`](/slides/python-net/de/aspose.slides/iconnector/y/) |  |
| [`width`](/slides/python-net/de/aspose.slides/iconnector/width/) |  |
| [`height`](/slides/python-net/de/aspose.slides/iconnector/height/) |  |
| [`alternative_text`](/slides/python-net/de/aspose.slides/iconnector/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/de/aspose.slides/iconnector/alternative_text_title/) |  |
| [`name`](/slides/python-net/de/aspose.slides/iconnector/name/) |  |
| [`is_decorative`](/slides/python-net/de/aspose.slides/iconnector/is_decorative/) |  |
| [`unique_id`](/slides/python-net/de/aspose.slides/iconnector/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/de/aspose.slides/iconnector/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/de/aspose.slides/iconnector/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/de/aspose.slides/iconnector/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/de/aspose.slides/iconnector/parent_group/) |  |
| [`slide`](/slides/python-net/de/aspose.slides/iconnector/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides/iconnector/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/de/aspose.slides/iconnector/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/de/aspose.slides/iconnector/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/de/aspose.slides/iconnector/hyperlink_manager/) |  |

## Methoden

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/de/aspose.slides/iconnector/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/de/aspose.slides/iconnector/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/de/aspose.slides/iconnector/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/de/aspose.slides/iconnector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`reroute(self)`](/slides/python-net/de/aspose.slides/iconnector/reroute/#) | Leitet den Connector um, sodass er den kürzesten möglichen Pfad zwischen den Formen, die er verbindet, nimmt. |
| [`get_geometry_paths(self)`](/slides/python-net/de/aspose.slides/iconnector/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/de/aspose.slides/iconnector/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/de/aspose.slides/iconnector/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/de/aspose.slides/iconnector/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/de/aspose.slides/iconnector/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/de/aspose.slides/iconnector/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/de/aspose.slides/iconnector/get_base_placeholder/#) |  |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)