---
title: IAutoShape class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/iautoshape/
---
## IAutoShape klasse

Stelt een AutoShape voor.

Het IAutoShape-type geeft de volgende leden weer:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`shape_lock`](/slides/python-net/nl/aspose.slides/iautoshape/shape_lock/) | Retourneert de vergrendelingen van de vorm.<br/>            Alleen-lezen [`IAutoShapeLock`](/slides/python-net/nl/aspose.slides/iautoshapelock). |
| [`auto_shape_lock`](/slides/python-net/nl/aspose.slides/iautoshape/auto_shape_lock/) | Retourneert de vergrendelingen van de AutoShape.<br/>            Alleen-lezen [`IAutoShapeLock`](/slides/python-net/nl/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/nl/aspose.slides/iautoshape/text_frame/) | Retourneert TextFrame-object voor de AutoShape.<br/>            Alleen-lezen [`ITextFrame`](/slides/python-net/nl/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/nl/aspose.slides/iautoshape/use_background_fill/) | Bepaalt of deze autoshape moet worden gevuld met de achtergrondvulling van de dia in plaats van gespecificeerd door stijl of vulformaat.<br/>            Lezen/Schrijven **bool**. |
| [`is_text_box`](/slides/python-net/nl/aspose.slides/iautoshape/is_text_box/) |  |
| [`shape_style`](/slides/python-net/nl/aspose.slides/iautoshape/shape_style/) |  |
| [`shape_type`](/slides/python-net/nl/aspose.slides/iautoshape/shape_type/) |  |
| [`adjustments`](/slides/python-net/nl/aspose.slides/iautoshape/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/nl/aspose.slides/iautoshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/nl/aspose.slides/iautoshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/nl/aspose.slides/iautoshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/nl/aspose.slides/iautoshape/raw_frame/) |  |
| [`frame`](/slides/python-net/nl/aspose.slides/iautoshape/frame/) |  |
| [`line_format`](/slides/python-net/nl/aspose.slides/iautoshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/nl/aspose.slides/iautoshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/nl/aspose.slides/iautoshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/nl/aspose.slides/iautoshape/fill_format/) |  |
| [`hidden`](/slides/python-net/nl/aspose.slides/iautoshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/nl/aspose.slides/iautoshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/nl/aspose.slides/iautoshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/nl/aspose.slides/iautoshape/rotation/) |  |
| [`x`](/slides/python-net/nl/aspose.slides/iautoshape/x/) |  |
| [`y`](/slides/python-net/nl/aspose.slides/iautoshape/y/) |  |
| [`width`](/slides/python-net/nl/aspose.slides/iautoshape/width/) |  |
| [`height`](/slides/python-net/nl/aspose.slides/iautoshape/height/) |  |
| [`alternative_text`](/slides/python-net/nl/aspose.slides/iautoshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/nl/aspose.slides/iautoshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/nl/aspose.slides/iautoshape/name/) |  |
| [`is_decorative`](/slides/python-net/nl/aspose.slides/iautoshape/is_decorative/) |  |
| [`unique_id`](/slides/python-net/nl/aspose.slides/iautoshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/nl/aspose.slides/iautoshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/nl/aspose.slides/iautoshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/nl/aspose.slides/iautoshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/nl/aspose.slides/iautoshape/parent_group/) |  |
| [`slide`](/slides/python-net/nl/aspose.slides/iautoshape/slide/) |  |
| [`presentation`](/slides/python-net/nl/aspose.slides/iautoshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/nl/aspose.slides/iautoshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/nl/aspose.slides/iautoshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/nl/aspose.slides/iautoshape/hyperlink_manager/) |  |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_image(self)`](/slides/python-net/nl/aspose.slides/iautoshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/nl/aspose.slides/iautoshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/nl/aspose.slides/iautoshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/nl/aspose.slides/iautoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`add_text_frame(self, text)`](/slides/python-net/nl/aspose.slides/iautoshape/add_text_frame/#str) | Voegt een nieuw TextFrame toe aan een vorm.<br/>            Als de vorm al een TextFrame heeft, wordt de tekst eenvoudigweg gewijzigd. |
| [`get_geometry_paths(self)`](/slides/python-net/nl/aspose.slides/iautoshape/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/nl/aspose.slides/iautoshape/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/nl/aspose.slides/iautoshape/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/nl/aspose.slides/iautoshape/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/nl/aspose.slides/iautoshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/nl/aspose.slides/iautoshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/nl/aspose.slides/iautoshape/get_base_placeholder/#) |  |

### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)