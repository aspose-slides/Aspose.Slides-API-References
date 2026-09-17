---
title: IConnector class
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides/iconnector/
---
## IConnector classe

Représente un connecteur.

Le type IConnector expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`shape_lock`](/slides/python-net/fr/aspose.slides/iconnector/shape_lock/) | Renvoie les verrous de la forme.<br/>            Lecture seule [`IConnectorLock`](/slides/python-net/fr/aspose.slides/iconnectorlock). |
| [`connector_lock`](/slides/python-net/fr/aspose.slides/iconnector/connector_lock/) | Renvoie les verrous du connecteur.<br/>            Lecture seule [`IConnectorLock`](/slides/python-net/fr/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/fr/aspose.slides/iconnector/start_shape_connected_to/) | Renvoie ou définit la forme à laquelle attacher le début du connecteur.<br/>            Lecture/écriture [`IShape`](/slides/python-net/fr/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/fr/aspose.slides/iconnector/end_shape_connected_to/) | Renvoie ou définit la forme à laquelle attacher l'extrémité du connecteur.<br/>            Lecture/écriture [`IShape`](/slides/python-net/fr/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/fr/aspose.slides/iconnector/start_shape_connection_site_index/) | Renvoie ou définit l'index du point de connexion pour la forme de départ.<br/>            Lecture/écriture **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/fr/aspose.slides/iconnector/end_shape_connection_site_index/) | Renvoie ou définit l'index du point de connexion pour la forme d'arrivée.<br/>            Lecture/écriture **int**. |
| [`shape_style`](/slides/python-net/fr/aspose.slides/iconnector/shape_style/) |  |
| [`shape_type`](/slides/python-net/fr/aspose.slides/iconnector/shape_type/) |  |
| [`adjustments`](/slides/python-net/fr/aspose.slides/iconnector/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/fr/aspose.slides/iconnector/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/fr/aspose.slides/iconnector/placeholder/) |  |
| [`custom_data`](/slides/python-net/fr/aspose.slides/iconnector/custom_data/) |  |
| [`raw_frame`](/slides/python-net/fr/aspose.slides/iconnector/raw_frame/) |  |
| [`frame`](/slides/python-net/fr/aspose.slides/iconnector/frame/) |  |
| [`line_format`](/slides/python-net/fr/aspose.slides/iconnector/line_format/) |  |
| [`three_d_format`](/slides/python-net/fr/aspose.slides/iconnector/three_d_format/) |  |
| [`effect_format`](/slides/python-net/fr/aspose.slides/iconnector/effect_format/) |  |
| [`fill_format`](/slides/python-net/fr/aspose.slides/iconnector/fill_format/) |  |
| [`hidden`](/slides/python-net/fr/aspose.slides/iconnector/hidden/) |  |
| [`z_order_position`](/slides/python-net/fr/aspose.slides/iconnector/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/fr/aspose.slides/iconnector/connection_site_count/) |  |
| [`rotation`](/slides/python-net/fr/aspose.slides/iconnector/rotation/) |  |
| [`x`](/slides/python-net/fr/aspose.slides/iconnector/x/) |  |
| [`y`](/slides/python-net/fr/aspose.slides/iconnector/y/) |  |
| [`width`](/slides/python-net/fr/aspose.slides/iconnector/width/) |  |
| [`height`](/slides/python-net/fr/aspose.slides/iconnector/height/) |  |
| [`alternative_text`](/slides/python-net/fr/aspose.slides/iconnector/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/fr/aspose.slides/iconnector/alternative_text_title/) |  |
| [`name`](/slides/python-net/fr/aspose.slides/iconnector/name/) |  |
| [`is_decorative`](/slides/python-net/fr/aspose.slides/iconnector/is_decorative/) |  |
| [`unique_id`](/slides/python-net/fr/aspose.slides/iconnector/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/fr/aspose.slides/iconnector/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/fr/aspose.slides/iconnector/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/fr/aspose.slides/iconnector/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/fr/aspose.slides/iconnector/parent_group/) |  |
| [`slide`](/slides/python-net/fr/aspose.slides/iconnector/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides/iconnector/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/fr/aspose.slides/iconnector/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/fr/aspose.slides/iconnector/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/fr/aspose.slides/iconnector/hyperlink_manager/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fr/aspose.slides/iconnector/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fr/aspose.slides/iconnector/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/fr/aspose.slides/iconnector/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fr/aspose.slides/iconnector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`reroute(self)`](/slides/python-net/fr/aspose.slides/iconnector/reroute/#) | Redirige le connecteur afin qu'il prenne le chemin le plus court entre les formes qu'il relie. |
| [`get_geometry_paths(self)`](/slides/python-net/fr/aspose.slides/iconnector/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/fr/aspose.slides/iconnector/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/fr/aspose.slides/iconnector/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/fr/aspose.slides/iconnector/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fr/aspose.slides/iconnector/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/fr/aspose.slides/iconnector/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/fr/aspose.slides/iconnector/get_base_placeholder/#) |  |

### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)