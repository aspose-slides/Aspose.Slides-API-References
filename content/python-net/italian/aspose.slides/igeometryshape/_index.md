---
title: IGeometryShape class
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/igeometryshape/
---
## IGeometryShape classe

Rappresenta la classe padre per tutte le forme geometriche.

Il tipo IGeometryShape espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`shape_style`](/slides/python-net/it/aspose.slides/igeometryshape/shape_style/) | Restituisce l'oggetto stile della forma.<br/>            Solo lettura [`IShapeStyle`](/slides/python-net/it/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/it/aspose.slides/igeometryshape/shape_type/) | Restituisce o imposta il tipo predefinito della geometria.<br/>            Nota: al cambiamento del valore tutti i valori di regolazione verranno ripristinati ai valori predefiniti.<br/>            Lettura/scrittura [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/it/aspose.slides/igeometryshape/adjustments/) | Restituisce una collezione dei valori di regolazione della forma.<br/>            Solo lettura [`IAdjustValueCollection`](/slides/python-net/it/aspose.slides/iadjustvaluecollection). |
| [`is_text_holder`](/slides/python-net/it/aspose.slides/igeometryshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/it/aspose.slides/igeometryshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/it/aspose.slides/igeometryshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/it/aspose.slides/igeometryshape/raw_frame/) |  |
| [`frame`](/slides/python-net/it/aspose.slides/igeometryshape/frame/) |  |
| [`line_format`](/slides/python-net/it/aspose.slides/igeometryshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/it/aspose.slides/igeometryshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/it/aspose.slides/igeometryshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/it/aspose.slides/igeometryshape/fill_format/) |  |
| [`hidden`](/slides/python-net/it/aspose.slides/igeometryshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/it/aspose.slides/igeometryshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/it/aspose.slides/igeometryshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/it/aspose.slides/igeometryshape/rotation/) |  |
| [`x`](/slides/python-net/it/aspose.slides/igeometryshape/x/) |  |
| [`y`](/slides/python-net/it/aspose.slides/igeometryshape/y/) |  |
| [`width`](/slides/python-net/it/aspose.slides/igeometryshape/width/) |  |
| [`height`](/slides/python-net/it/aspose.slides/igeometryshape/height/) |  |
| [`alternative_text`](/slides/python-net/it/aspose.slides/igeometryshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/it/aspose.slides/igeometryshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/it/aspose.slides/igeometryshape/name/) |  |
| [`is_decorative`](/slides/python-net/it/aspose.slides/igeometryshape/is_decorative/) |  |
| [`shape_lock`](/slides/python-net/it/aspose.slides/igeometryshape/shape_lock/) |  |
| [`unique_id`](/slides/python-net/it/aspose.slides/igeometryshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/it/aspose.slides/igeometryshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/it/aspose.slides/igeometryshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/it/aspose.slides/igeometryshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/it/aspose.slides/igeometryshape/parent_group/) |  |
| [`slide`](/slides/python-net/it/aspose.slides/igeometryshape/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides/igeometryshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/it/aspose.slides/igeometryshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/it/aspose.slides/igeometryshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/it/aspose.slides/igeometryshape/hyperlink_manager/) |  |

## Metodi

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/it/aspose.slides/igeometryshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/it/aspose.slides/igeometryshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/it/aspose.slides/igeometryshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/it/aspose.slides/igeometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/it/aspose.slides/igeometryshape/get_geometry_paths/#) | Restituisce la copia del percorso della forma geometrica. Le coordinate sono relative all'angolo superiore sinistro della forma. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/it/aspose.slides/igeometryshape/set_geometry_path/#igeometrypath) | Aggiorna la geometria della forma dall'oggetto [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath). Le coordinate devono essere relative al lato sinistro<br/>             angolo superiore della forma.<br/>             Cambia il tipo della forma ([`IGeometryShape.shape_type`](/slides/python-net/it/aspose.slides/igeometryshape/shape_type)) in [`ShapeType.CUSTOM`](/slides/python-net/it/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/it/aspose.slides/igeometryshape/set_geometry_paths/#listigeometrypath) | Aggiorna la geometria della forma da un array di [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath). Le coordinate devono essere relative al lato sinistro<br/>             angolo superiore della forma.<br/>             Cambia il tipo della forma ([`IGeometryShape.shape_type`](/slides/python-net/it/aspose.slides/igeometryshape/shape_type)) in [`ShapeType.CUSTOM`](/slides/python-net/it/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/it/aspose.slides/igeometryshape/create_shape_elements/#) | Crea e restituisce un array degli elementi della forma. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/it/aspose.slides/igeometryshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/it/aspose.slides/igeometryshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/it/aspose.slides/igeometryshape/get_base_placeholder/#) |  |


### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)