---
title: IGeometryShape class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/igeometryshape/
---
## IGeometryShape klass

Representerar basklassen för alla geometriska former.

Typen IGeometryShape exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`shape_style`](/slides/python-net/sv/aspose.slides/igeometryshape/shape_style/) | Returnerar formens stilobjekt.<br/>            Skrivskyddad [`IShapeStyle`](/slides/python-net/sv/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/sv/aspose.slides/igeometryshape/shape_type/) | Returnerar eller anger geometrisk förinställningstyp.<br/>            Obs: vid värdeförändring återställs alla justeringsvärden till sina standardvärden.<br/>            Läs/skriv [`ShapeType`](/slides/python-net/sv/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/sv/aspose.slides/igeometryshape/adjustments/) | Returnerar en samling av formens justeringsvärden.<br/>            Skrivskyddad [`IAdjustValueCollection`](/slides/python-net/sv/aspose.slides/iadjustvaluecollection). |
| [`is_text_holder`](/slides/python-net/sv/aspose.slides/igeometryshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/sv/aspose.slides/igeometryshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/sv/aspose.slides/igeometryshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/sv/aspose.slides/igeometryshape/raw_frame/) |  |
| [`frame`](/slides/python-net/sv/aspose.slides/igeometryshape/frame/) |  |
| [`line_format`](/slides/python-net/sv/aspose.slides/igeometryshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/sv/aspose.slides/igeometryshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/sv/aspose.slides/igeometryshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/sv/aspose.slides/igeometryshape/fill_format/) |  |
| [`hidden`](/slides/python-net/sv/aspose.slides/igeometryshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/sv/aspose.slides/igeometryshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/sv/aspose.slides/igeometryshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/sv/aspose.slides/igeometryshape/rotation/) |  |
| [`x`](/slides/python-net/sv/aspose.slides/igeometryshape/x/) |  |
| [`y`](/slides/python-net/sv/aspose.slides/igeometryshape/y/) |  |
| [`width`](/slides/python-net/sv/aspose.slides/igeometryshape/width/) |  |
| [`height`](/slides/python-net/sv/aspose.slides/igeometryshape/height/) |  |
| [`alternative_text`](/slides/python-net/sv/aspose.slides/igeometryshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/sv/aspose.slides/igeometryshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/sv/aspose.slides/igeometryshape/name/) |  |
| [`is_decorative`](/slides/python-net/sv/aspose.slides/igeometryshape/is_decorative/) |  |
| [`shape_lock`](/slides/python-net/sv/aspose.slides/igeometryshape/shape_lock/) |  |
| [`unique_id`](/slides/python-net/sv/aspose.slides/igeometryshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/sv/aspose.slides/igeometryshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/sv/aspose.slides/igeometryshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/sv/aspose.slides/igeometryshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/sv/aspose.slides/igeometryshape/parent_group/) |  |
| [`slide`](/slides/python-net/sv/aspose.slides/igeometryshape/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides/igeometryshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/sv/aspose.slides/igeometryshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/sv/aspose.slides/igeometryshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/sv/aspose.slides/igeometryshape/hyperlink_manager/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_image(self)`](/slides/python-net/sv/aspose.slides/igeometryshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides/igeometryshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/sv/aspose.slides/igeometryshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/sv/aspose.slides/igeometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/sv/aspose.slides/igeometryshape/get_geometry_paths/#) | Returnerar en kopia av geometrisk formens väg. Koordinaterna är relativa till formens vänstra övre hörn. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/sv/aspose.slides/igeometryshape/set_geometry_path/#igeometrypath) | Uppdaterar formens geometri från [`IGeometryPath`](/slides/python-net/sv/aspose.slides/igeometrypath)-objektet. Koordinaterna måste vara relativa till den vänstra<br/>             övre hörnet av formen.<br/>             Ändrar formens typ ([`IGeometryShape.shape_type`](/slides/python-net/sv/aspose.slides/igeometryshape/shape_type)) till [`ShapeType.CUSTOM`](/slides/python-net/sv/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/sv/aspose.slides/igeometryshape/set_geometry_paths/#listigeometrypath) | Uppdaterar formens geometri från en array av [`IGeometryPath`](/slides/python-net/sv/aspose.slides/igeometrypath). Koordinaterna måste vara relativa till den vänstra<br/>             övre hörnet av formen.<br/>             Ändrar formens typ ([`IGeometryShape.shape_type`](/slides/python-net/sv/aspose.slides/igeometryshape/shape_type)) till [`ShapeType.CUSTOM`](/slides/python-net/sv/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/sv/aspose.slides/igeometryshape/create_shape_elements/#) | Skapar och returnerar en array av formens element. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/sv/aspose.slides/igeometryshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/sv/aspose.slides/igeometryshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/sv/aspose.slides/igeometryshape/get_base_placeholder/#) |  |

### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)