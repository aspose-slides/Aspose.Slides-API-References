---
title: IPictureFrame class
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides/ipictureframe/
---
## IPictureFrame classe

Représente un cadre contenant une image.

Le type IPictureFrame expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`shape_lock`](/slides/python-net/fr/aspose.slides/ipictureframe/shape_lock/) | Renvoie les verrous de la forme.<br/>            Lecture seule [`IPictureFrameLock`](/slides/python-net/fr/aspose.slides/ipictureframelock). |
| [`picture_frame_lock`](/slides/python-net/fr/aspose.slides/ipictureframe/picture_frame_lock/) | Renvoie les verrous de PictureFrame.<br/>            Lecture seule [`IPictureFrameLock`](/slides/python-net/fr/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/fr/aspose.slides/ipictureframe/picture_format/) | Renvoie l'objet PictureFillFormat pour un cadre image.<br/>            Lecture seule [`IPictureFillFormat`](/slides/python-net/fr/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/fr/aspose.slides/ipictureframe/relative_scale_height/) | Renvoie ou définit l'échelle de hauteur (relative à la taille originale de l'image) du cadre image. La valeur 1.0 correspond à 100 %.<br/>            Lecture/écriture **float**. |
| [`relative_scale_width`](/slides/python-net/fr/aspose.slides/ipictureframe/relative_scale_width/) | Renvoie ou définit l'échelle de largeur (relative à la taille originale de l'image) du cadre image. La valeur 1.0 correspond à 100 %.<br/>            Lecture/écriture **float**. |
| [`shape_style`](/slides/python-net/fr/aspose.slides/ipictureframe/shape_style/) |  |
| [`shape_type`](/slides/python-net/fr/aspose.slides/ipictureframe/shape_type/) |  |
| [`adjustments`](/slides/python-net/fr/aspose.slides/ipictureframe/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/fr/aspose.slides/ipictureframe/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/fr/aspose.slides/ipictureframe/placeholder/) |  |
| [`custom_data`](/slides/python-net/fr/aspose.slides/ipictureframe/custom_data/) |  |
| [`raw_frame`](/slides/python-net/fr/aspose.slides/ipictureframe/raw_frame/) |  |
| [`frame`](/slides/python-net/fr/aspose.slides/ipictureframe/frame/) |  |
| [`line_format`](/slides/python-net/fr/aspose.slides/ipictureframe/line_format/) |  |
| [`three_d_format`](/slides/python-net/fr/aspose.slides/ipictureframe/three_d_format/) |  |
| [`effect_format`](/slides/python-net/fr/aspose.slides/ipictureframe/effect_format/) |  |
| [`fill_format`](/slides/python-net/fr/aspose.slides/ipictureframe/fill_format/) |  |
| [`hidden`](/slides/python-net/fr/aspose.slides/ipictureframe/hidden/) |  |
| [`z_order_position`](/slides/python-net/fr/aspose.slides/ipictureframe/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/fr/aspose.slides/ipictureframe/connection_site_count/) |  |
| [`rotation`](/slides/python-net/fr/aspose.slides/ipictureframe/rotation/) |  |
| [`x`](/slides/python-net/fr/aspose.slides/ipictureframe/x/) |  |
| [`y`](/slides/python-net/fr/aspose.slides/ipictureframe/y/) |  |
| [`width`](/slides/python-net/fr/aspose.slides/ipictureframe/width/) |  |
| [`height`](/slides/python-net/fr/aspose.slides/ipictureframe/height/) |  |
| [`alternative_text`](/slides/python-net/fr/aspose.slides/ipictureframe/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/fr/aspose.slides/ipictureframe/alternative_text_title/) |  |
| [`name`](/slides/python-net/fr/aspose.slides/ipictureframe/name/) |  |
| [`is_decorative`](/slides/python-net/fr/aspose.slides/ipictureframe/is_decorative/) |  |
| [`unique_id`](/slides/python-net/fr/aspose.slides/ipictureframe/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/fr/aspose.slides/ipictureframe/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/fr/aspose.slides/ipictureframe/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/fr/aspose.slides/ipictureframe/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/fr/aspose.slides/ipictureframe/parent_group/) |  |
| [`slide`](/slides/python-net/fr/aspose.slides/ipictureframe/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides/ipictureframe/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/fr/aspose.slides/ipictureframe/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/fr/aspose.slides/ipictureframe/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/fr/aspose.slides/ipictureframe/hyperlink_manager/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fr/aspose.slides/ipictureframe/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fr/aspose.slides/ipictureframe/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/fr/aspose.slides/ipictureframe/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fr/aspose.slides/ipictureframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/fr/aspose.slides/ipictureframe/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/fr/aspose.slides/ipictureframe/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/fr/aspose.slides/ipictureframe/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/fr/aspose.slides/ipictureframe/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fr/aspose.slides/ipictureframe/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/fr/aspose.slides/ipictureframe/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/fr/aspose.slides/ipictureframe/get_base_placeholder/#) |  |

### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)