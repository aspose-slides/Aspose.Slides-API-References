---
title: IGeometryShape class
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides/igeometryshape/
---
## IGeometryShape classe

Représente la classe parente de toutes les formes géométriques.

Le type IGeometryShape expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`shape_style`](/slides/python-net/fr/aspose.slides/igeometryshape/shape_style/) | Renvoie l'objet de style de la forme.<br/>            Lecture seule [`IShapeStyle`](/slides/python-net/fr/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/fr/aspose.slides/igeometryshape/shape_type/) | Renvoie ou définit le type de préréglage géométrique.<br/>            Remarque : lors du changement de valeur, toutes les valeurs d'ajustement seront réinitialisées à leurs valeurs par défaut.<br/>            Lecture/écriture [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/fr/aspose.slides/igeometryshape/adjustments/) | Renvoie une collection des valeurs d'ajustement de la forme.<br/>            Lecture seule [`IAdjustValueCollection`](/slides/python-net/fr/aspose.slides/iadjustvaluecollection). |
| [`is_text_holder`](/slides/python-net/fr/aspose.slides/igeometryshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/fr/aspose.slides/igeometryshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/fr/aspose.slides/igeometryshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/fr/aspose.slides/igeometryshape/raw_frame/) |  |
| [`frame`](/slides/python-net/fr/aspose.slides/igeometryshape/frame/) |  |
| [`line_format`](/slides/python-net/fr/aspose.slides/igeometryshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/fr/aspose.slides/igeometryshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/fr/aspose.slides/igeometryshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/fr/aspose.slides/igeometryshape/fill_format/) |  |
| [`hidden`](/slides/python-net/fr/aspose.slides/igeometryshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/fr/aspose.slides/igeometryshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/fr/aspose.slides/igeometryshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/fr/aspose.slides/igeometryshape/rotation/) |  |
| [`x`](/slides/python-net/fr/aspose.slides/igeometryshape/x/) |  |
| [`y`](/slides/python-net/fr/aspose.slides/igeometryshape/y/) |  |
| [`width`](/slides/python-net/fr/aspose.slides/igeometryshape/width/) |  |
| [`height`](/slides/python-net/fr/aspose.slides/igeometryshape/height/) |  |
| [`alternative_text`](/slides/python-net/fr/aspose.slides/igeometryshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/fr/aspose.slides/igeometryshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/fr/aspose.slides/igeometryshape/name/) |  |
| [`is_decorative`](/slides/python-net/fr/aspose.slides/igeometryshape/is_decorative/) |  |
| [`shape_lock`](/slides/python-net/fr/aspose.slides/igeometryshape/shape_lock/) |  |
| [`unique_id`](/slides/python-net/fr/aspose.slides/igeometryshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/fr/aspose.slides/igeometryshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/fr/aspose.slides/igeometryshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/fr/aspose.slides/igeometryshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/fr/aspose.slides/igeometryshape/parent_group/) |  |
| [`slide`](/slides/python-net/fr/aspose.slides/igeometryshape/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides/igeometryshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/fr/aspose.slides/igeometryshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/fr/aspose.slides/igeometryshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/fr/aspose.slides/igeometryshape/hyperlink_manager/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/fr/aspose.slides/igeometryshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/fr/aspose.slides/igeometryshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/fr/aspose.slides/igeometryshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/fr/aspose.slides/igeometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/fr/aspose.slides/igeometryshape/get_geometry_paths/#) | Renvoie la copie du tracé de la forme géométrique. Les coordonnées sont relatives au coin supérieur gauche de la forme. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/fr/aspose.slides/igeometryshape/set_geometry_path/#igeometrypath) | Met à jour la géométrie de la forme à partir de l'objet [`IGeometryPath`](/slides/python-net/fr/aspose.slides/igeometrypath). Les coordonnées doivent être relatives au coin supérieur gauche de la forme.<br/>             Change le type de la forme ([`IGeometryShape.shape_type`](/slides/python-net/fr/aspose.slides/igeometryshape/shape_type)) en [`ShapeType.CUSTOM`](/slides/python-net/fr/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/fr/aspose.slides/igeometryshape/set_geometry_paths/#listigeometrypath) | Met à jour la géométrie de la forme à partir d'un tableau de [`IGeometryPath`](/slides/python-net/fr/aspose.slides/igeometrypath). Les coordonnées doivent être relatives au coin supérieur gauche de la forme.<br/>             Change le type de la forme ([`IGeometryShape.shape_type`](/slides/python-net/fr/aspose.slides/igeometryshape/shape_type)) en [`ShapeType.CUSTOM`](/slides/python-net/fr/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/fr/aspose.slides/igeometryshape/create_shape_elements/#) | Crée et renvoie un tableau des éléments de la forme. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/fr/aspose.slides/igeometryshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/fr/aspose.slides/igeometryshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/fr/aspose.slides/igeometryshape/get_base_placeholder/#) |  |


### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)