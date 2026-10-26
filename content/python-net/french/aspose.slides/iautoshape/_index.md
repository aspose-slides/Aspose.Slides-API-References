---
title: IAutoShape class
second_title: Aspose.Slides pour Python via l'API .NET
description: 
type: docs
url: /fr/aspose.slides/iautoshape/
---
## IAutoShape classe

Représente une AutoShape.

Le type IAutoShape expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`shape_lock`](/slides/python-net/fr/aspose.slides/iautoshape/shape_lock/) | Renvoie les verrous de la forme.<br/>            Lecture seule [`IAutoShapeLock`](/slides/python-net/fr/aspose.slides/iautoshapelock). |
| [`auto_shape_lock`](/slides/python-net/fr/aspose.slides/iautoshape/auto_shape_lock/) | Renvoie les verrous de l'AutoShape.<br/>            Lecture seule [`IAutoShapeLock`](/slides/python-net/fr/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/fr/aspose.slides/iautoshape/text_frame/) | Renvoie l'objet TextFrame pour l'AutoShape.<br/>            Lecture seule [`ITextFrame`](/slides/python-net/fr/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/fr/aspose.slides/iautoshape/use_background_fill/) | Détermine si cet autoshape doit être rempli avec le remplissage d'arrière-plan de la diapositive au lieu de celui spécifié par le style ou le format de remplissage.<br/>            Lecture/écriture **bool**. |
| [`is_text_box`](/slides/python-net/fr/aspose.slides/iautoshape/is_text_box/) | Spécifie si la forme est une zone de texte. |
| [`shape_style`](/slides/python-net/fr/aspose.slides/iautoshape/shape_style/) |  |
| [`shape_type`](/slides/python-net/fr/aspose.slides/iautoshape/shape_type/) |  |
| [`adjustments`](/slides/python-net/fr/aspose.slides/iautoshape/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/fr/aspose.slides/iautoshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/fr/aspose.slides/iautoshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/fr/aspose.slides/iautoshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/fr/aspose.slides/iautoshape/raw_frame/) |  |
| [`frame`](/slides/python-net/fr/aspose.slides/iautoshape/frame/) |  |
| [`line_format`](/slides/python-net/fr/aspose.slides/iautoshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/fr/aspose.slides/iautoshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/fr/aspose.slides/iautoshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/fr/aspose.slides/iautoshape/fill_format/) |  |
| [`hidden`](/slides/python-net/fr/aspose.slides/iautoshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/fr/aspose.slides/iautoshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/fr/aspose.slides/iautoshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/fr/aspose.slides/iautoshape/rotation/) |  |
| [`x`](/slides/python-net/fr/aspose.slides/iautoshape/x/) |  |
| [`y`](/slides/python-net/fr/aspose.slides/iautoshape/y/) |  |
| [`width`](/slides/python-net/fr/aspose.slides/iautoshape/width/) |  |
| [`height`](/slides/python-net/fr/aspose.slides/iautoshape/height/) |  |
| [`alternative_text`](/slides/python-net/fr/aspose.slides/iautoshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/fr/aspose.slides/iautoshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/fr/aspose.slides/iautoshape/name/) |  |
| [`is_decorative`](/slides/python-net/fr/aspose.slides/iautoshape/is_decorative/) |  |
| [`unique_id`](/slides/python-net/fr/aspose.slides/iautoshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/fr/aspose.slides/iautoshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/fr/aspose.slides/iautoshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/fr/aspose.slides/iautoshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/fr/aspose.slides/iautoshape/parent_group/) |  |
| [`slide`](/slides/python-net/fr/aspose.slides/iautoshape/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides/iautoshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/fr/aspose.slides/iautoshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/fr/aspose.slides/iautoshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/fr/aspose.slides/iautoshape/hyperlink_manager/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fr/aspose.slides/iautoshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fr/aspose.slides/iautoshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/fr/aspose.slides/iautoshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fr/aspose.slides/iautoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`add_text_frame(self, text)`](/slides/python-net/fr/aspose.slides/iautoshape/add_text_frame/#str) | Ajoute un nouveau TextFrame à une forme.<br/>            Si la forme possède déjà un TextFrame, il modifie simplement son texte. |
| [`get_geometry_paths(self)`](/slides/python-net/fr/aspose.slides/iautoshape/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/fr/aspose.slides/iautoshape/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/fr/aspose.slides/iautoshape/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/fr/aspose.slides/iautoshape/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fr/aspose.slides/iautoshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/fr/aspose.slides/iautoshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/fr/aspose.slides/iautoshape/get_base_placeholder/#) |  |

### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)