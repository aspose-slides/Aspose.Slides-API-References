---
title: IConnector class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/iconnector/
---
## IConnector klasse

Representeert een connector.

Het IConnector-type biedt de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`shape_lock`](/slides/python-net/nl/aspose.slides/iconnector/shape_lock/) | Retourneert de vergrendelingen van de shape.<br/>            Alleen-lezen [`IConnectorLock`](/slides/python-net/nl/aspose.slides/iconnectorlock). |
| [`connector_lock`](/slides/python-net/nl/aspose.slides/iconnector/connector_lock/) | Retourneert de vergrendelingen van de Connector.<br/>            Alleen-lezen [`IConnectorLock`](/slides/python-net/nl/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/nl/aspose.slides/iconnector/start_shape_connected_to/) | Retourneert of stelt de shape in waaraan het begin van de connector wordt gekoppeld.<br/>            Lezen/Schrijven [`IShape`](/slides/python-net/nl/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/nl/aspose.slides/iconnector/end_shape_connected_to/) | Retourneert of stelt de shape in waaraan het einde van de connector wordt gekoppeld.<br/>            Lezen/Schrijven [`IShape`](/slides/python-net/nl/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/nl/aspose.slides/iconnector/start_shape_connection_site_index/) | Retourneert of stelt de index van de aansluitingsplaats voor de start-shape in.<br/>            Lezen/Schrijven **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/nl/aspose.slides/iconnector/end_shape_connection_site_index/) | Retourneert of stelt de index van de aansluitingsplaats voor de eind-shape in.<br/>            Lezen/Schrijven **int**. |
| [`shape_style`](/slides/python-net/nl/aspose.slides/iconnector/shape_style/) |  |
| [`shape_type`](/slides/python-net/nl/aspose.slides/iconnector/shape_type/) |  |
| [`adjustments`](/slides/python-net/nl/aspose.slides/iconnector/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/nl/aspose.slides/iconnector/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/nl/aspose.slides/iconnector/placeholder/) |  |
| [`custom_data`](/slides/python-net/nl/aspose.slides/iconnector/custom_data/) |  |
| [`raw_frame`](/slides/python-net/nl/aspose.slides/iconnector/raw_frame/) |  |
| [`frame`](/slides/python-net/nl/aspose.slides/iconnector/frame/) |  |
| [`line_format`](/slides/python-net/nl/aspose.slides/iconnector/line_format/) |  |
| [`three_d_format`](/slides/python-net/nl/aspose.slides/iconnector/three_d_format/) |  |
| [`effect_format`](/slides/python-net/nl/aspose.slides/iconnector/effect_format/) |  |
| [`fill_format`](/slides/python-net/nl/aspose.slides/iconnector/fill_format/) |  |
| [`hidden`](/slides/python-net/nl/aspose.slides/iconnector/hidden/) |  |
| [`z_order_position`](/slides/python-net/nl/aspose.slides/iconnector/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/nl/aspose.slides/iconnector/connection_site_count/) |  |
| [`rotation`](/slides/python-net/nl/aspose.slides/iconnector/rotation/) |  |
| [`x`](/slides/python-net/nl/aspose.slides/iconnector/x/) |  |
| [`y`](/slides/python-net/nl/aspose.slides/iconnector/y/) |  |
| [`width`](/slides/python-net/nl/aspose.slides/iconnector/width/) |  |
| [`height`](/slides/python-net/nl/aspose.slides/iconnector/height/) |  |
| [`alternative_text`](/slides/python-net/nl/aspose.slides/iconnector/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/nl/aspose.slides/iconnector/alternative_text_title/) |  |
| [`name`](/slides/python-net/nl/aspose.slides/iconnector/name/) |  |
| [`is_decorative`](/slides/python-net/nl/aspose.slides/iconnector/is_decorative/) |  |
| [`unique_id`](/slides/python-net/nl/aspose.slides/iconnector/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/nl/aspose.slides/iconnector/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/nl/aspose.slides/iconnector/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/nl/aspose.slides/iconnector/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/nl/aspose.slides/iconnector/parent_group/) |  |
| [`slide`](/slides/python-net/nl/aspose.slides/iconnector/slide/) |  |
| [`presentation`](/slides/python-net/nl/aspose.slides/iconnector/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/nl/aspose.slides/iconnector/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/nl/aspose.slides/iconnector/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/nl/aspose.slides/iconnector/hyperlink_manager/) |  |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_image(self)`](/slides/python-net/nl/aspose.slides/iconnector/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides/iconnector/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/nl/aspose.slides/iconnector/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/nl/aspose.slides/iconnector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`reroute(self)`](/slides/python-net/nl/aspose.slides/iconnector/reroute/#) | Routet de connector opnieuw zodat hij het kortste mogelijke pad tussen de shapes die hij verbindt volgt. |
| [`get_geometry_paths(self)`](/slides/python-net/nl/aspose.slides/iconnector/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/nl/aspose.slides/iconnector/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/nl/aspose.slides/iconnector/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/nl/aspose.slides/iconnector/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/nl/aspose.slides/iconnector/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/nl/aspose.slides/iconnector/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/nl/aspose.slides/iconnector/get_base_placeholder/#) |  |

### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)