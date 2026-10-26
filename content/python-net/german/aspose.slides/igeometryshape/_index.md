---
title: IGeometryShape class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/igeometryshape/
---
## IGeometryShape Klasse

Stellt die Basisklasse für alle geometrischen Formen dar.

Der IGeometryShape-Typ stellt die folgenden Member bereit:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`shape_style`](/slides/python-net/de/aspose.slides/igeometryshape/shape_style/) | Gibt das Stilobjekt der Form zurück.<br/>Nur lesend [`IShapeStyle`](/slides/python-net/de/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/de/aspose.slides/igeometryshape/shape_type/) | Gibt den voreingestellten Geometrietyp zurück oder setzt ihn.<br/>Hinweis: Beim Ändern des Wertes werden alle Anpassungswerte auf ihre Standardwerte zurückgesetzt.<br/>Lese/Schreiben [`ShapeType`](/slides/python-net/de/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/de/aspose.slides/igeometryshape/adjustments/) | Gibt eine Sammlung der Anpassungswerte der Form zurück.<br/>Nur lesend [`IAdjustValueCollection`](/slides/python-net/de/aspose.slides/iadjustvaluecollection). |
| [`is_text_holder`](/slides/python-net/de/aspose.slides/igeometryshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/de/aspose.slides/igeometryshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/de/aspose.slides/igeometryshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/de/aspose.slides/igeometryshape/raw_frame/) |  |
| [`frame`](/slides/python-net/de/aspose.slides/igeometryshape/frame/) |  |
| [`line_format`](/slides/python-net/de/aspose.slides/igeometryshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/de/aspose.slides/igeometryshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/de/aspose.slides/igeometryshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/de/aspose.slides/igeometryshape/fill_format/) |  |
| [`hidden`](/slides/python-net/de/aspose.slides/igeometryshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/de/aspose.slides/igeometryshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/de/aspose.slides/igeometryshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/de/aspose.slides/igeometryshape/rotation/) |  |
| [`x`](/slides/python-net/de/aspose.slides/igeometryshape/x/) |  |
| [`y`](/slides/python-net/de/aspose.slides/igeometryshape/y/) |  |
| [`width`](/slides/python-net/de/aspose.slides/igeometryshape/width/) |  |
| [`height`](/slides/python-net/de/aspose.slides/igeometryshape/height/) |  |
| [`alternative_text`](/slides/python-net/de/aspose.slides/igeometryshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/de/aspose.slides/igeometryshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/de/aspose.slides/igeometryshape/name/) |  |
| [`is_decorative`](/slides/python-net/de/aspose.slides/igeometryshape/is_decorative/) |  |
| [`shape_lock`](/slides/python-net/de/aspose.slides/igeometryshape/shape_lock/) |  |
| [`unique_id`](/slides/python-net/de/aspose.slides/igeometryshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/de/aspose.slides/igeometryshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/de/aspose.slides/igeometryshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/de/aspose.slides/igeometryshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/de/aspose.slides/igeometryshape/parent_group/) |  |
| [`slide`](/slides/python-net/de/aspose.slides/igeometryshape/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides/igeometryshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/de/aspose.slides/igeometryshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/de/aspose.slides/igeometryshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/de/aspose.slides/igeometryshape/hyperlink_manager/) |  |

## Methoden

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/de/aspose.slides/igeometryshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/de/aspose.slides/igeometryshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/de/aspose.slides/igeometryshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/de/aspose.slides/igeometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/de/aspose.slides/igeometryshape/get_geometry_paths/#) | Gibt eine Kopie des Pfads der geometrischen Form zurück. Die Koordinaten sind relativ zur oberen linken Ecke der Form. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/de/aspose.slides/igeometryshape/set_geometry_path/#igeometrypath) | Aktualisiert die Geometrie der Form aus dem [`IGeometryPath`](/slides/python-net/de/aspose.slides/igeometrypath)-Objekt. Koordinaten müssen relativ zur oberen linken Ecke der Form sein. Ändert den Typ der Form ([`IGeometryShape.shape_type`](/slides/python-net/de/aspose.slides/igeometryshape/shape_type)) zu [`ShapeType.CUSTOM`](/slides/python-net/de/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/de/aspose.slides/igeometryshape/set_geometry_paths/#listigeometrypath) | Aktualisiert die Geometrie der Form aus einem Array von [`IGeometryPath`](/slides/python-net/de/aspose.slides/igeometrypath). Koordinaten müssen relativ zur oberen linken Ecke der Form sein. Ändert den Typ der Form ([`IGeometryShape.shape_type`](/slides/python-net/de/aspose.slides/igeometryshape/shape_type)) zu [`ShapeType.CUSTOM`](/slides/python-net/de/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/de/aspose.slides/igeometryshape/create_shape_elements/#) | Erstellt und gibt ein Array der Formelemente zurück. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/de/aspose.slides/igeometryshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/de/aspose.slides/igeometryshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/de/aspose.slides/igeometryshape/get_base_placeholder/#) |  |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)