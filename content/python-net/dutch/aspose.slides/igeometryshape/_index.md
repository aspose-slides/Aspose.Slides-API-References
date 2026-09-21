---
title: IGeometryShape class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/igeometryshape/
---
## IGeometryShape klasse

Stelt de bovenliggende klasse voor alle geometrische vormen voor.

Het IGeometryShape-type exposeert de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`shape_style`](/slides/python-net/nl/aspose.slides/igeometryshape/shape_style/) | Retourneert het stijlobject van de vorm.<br/>            Alleen-lezen [`IShapeStyle`](/slides/python-net/nl/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/nl/aspose.slides/igeometryshape/shape_type/) | Retourneert of stelt het geometrische voorinstellingstype in.<br/>            Opmerking: bij het wijzigen van de waarde worden alle aanpassingswaarden teruggezet naar hun standaardwaarden.<br/>            Lezen/schrijven [`ShapeType`](/slides/python-net/nl/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/nl/aspose.slides/igeometryshape/adjustments/) | Retourneert een verzameling van de aanpassingswaarden van de vorm.<br/>            Alleen-lezen [`IAdjustValueCollection`](/slides/python-net/nl/aspose.slides/iadjustvaluecollection). |
| [`is_text_holder`](/slides/python-net/nl/aspose.slides/igeometryshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/nl/aspose.slides/igeometryshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/nl/aspose.slides/igeometryshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/nl/aspose.slides/igeometryshape/raw_frame/) |  |
| [`frame`](/slides/python-net/nl/aspose.slides/igeometryshape/frame/) |  |
| [`line_format`](/slides/python-net/nl/aspose.slides/igeometryshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/nl/aspose.slides/igeometryshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/nl/aspose.slides/igeometryshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/nl/aspose.slides/igeometryshape/fill_format/) |  |
| [`hidden`](/slides/python-net/nl/aspose.slides/igeometryshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/nl/aspose.slides/igeometryshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/nl/aspose.slides/igeometryshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/nl/aspose.slides/igeometryshape/rotation/) |  |
| [`x`](/slides/python-net/nl/aspose.slides/igeometryshape/x/) |  |
| [`y`](/slides/python-net/nl/aspose.slides/igeometryshape/y/) |  |
| [`width`](/slides/python-net/nl/aspose.slides/igeometryshape/width/) |  |
| [`height`](/slides/python-net/nl/aspose.slides/igeometryshape/height/) |  |
| [`alternative_text`](/slides/python-net/nl/aspose.slides/igeometryshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/nl/aspose.slides/igeometryshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/nl/aspose.slides/igeometryshape/name/) |  |
| [`is_decorative`](/slides/python-net/nl/aspose.slides/igeometryshape/is_decorative/) |  |
| [`shape_lock`](/slides/python-net/nl/aspose.slides/igeometryshape/shape_lock/) |  |
| [`unique_id`](/slides/python-net/nl/aspose.slides/igeometryshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/nl/aspose.slides/igeometryshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/nl/aspose.slides/igeometryshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/nl/aspose.slides/igeometryshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/nl/aspose.slides/igeometryshape/parent_group/) |  |
| [`slide`](/slides/python-net/nl/aspose.slides/igeometryshape/slide/) |  |
| [`presentation`](/slides/python-net/nl/aspose.slides/igeometryshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/nl/aspose.slides/igeometryshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/nl/aspose.slides/igeometryshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/nl/aspose.slides/igeometryshape/hyperlink_manager/) |  |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_image(self)`](/slides/python-net/nl/aspose.slides/igeometryshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides/igeometryshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/nl/aspose.slides/igeometryshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/nl/aspose.slides/igeometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/nl/aspose.slides/igeometryshape/get_geometry_paths/#) | Retourneert een kopie van het pad van de geometrische vorm. Coördinaten zijn relatief ten opzichte van de linkerbovenhoek van de vorm. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/nl/aspose.slides/igeometryshape/set_geometry_path/#igeometrypath) | Werkt de vormgeometrie bij vanuit een [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath)-object. Coördinaten moeten relatief zijn ten opzichte van de linker-bovenhoek van de vorm.<br/>             Verandert het type van de vorm ([`IGeometryShape.shape_type`](/slides/python-net/nl/aspose.slides/igeometryshape/shape_type)) naar [`ShapeType.CUSTOM`](/slides/python-net/nl/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/nl/aspose.slides/igeometryshape/set_geometry_paths/#listigeometrypath) | Werkt de vormgeometrie bij vanuit een array van [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath). Coördinaten moeten relatief zijn ten opzichte van de linker-bovenhoek van de vorm.<br/>             Verandert het type van de vorm ([`IGeometryShape.shape_type`](/slides/python-net/nl/aspose.slides/igeometryshape/shape_type)) naar [`ShapeType.CUSTOM`](/slides/python-net/nl/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/nl/aspose.slides/igeometryshape/create_shape_elements/#) | Maakt en retourneert een array van de elementen van de vorm. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/nl/aspose.slides/igeometryshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/nl/aspose.slides/igeometryshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/nl/aspose.slides/igeometryshape/get_base_placeholder/#) |  |

### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)