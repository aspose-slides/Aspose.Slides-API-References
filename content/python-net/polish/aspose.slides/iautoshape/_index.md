---
title: IAutoShape class
second_title: Aspose.Slides dla Pythona poprzez .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/iautoshape/
---
## IAutoShape klasa

Reprezentuje AutoShape.

Typ IAutoShape udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`shape_lock`](/slides/python-net/pl/aspose.slides/iautoshape/shape_lock/) | Zwraca blokady kształtu.<br/>            Tylko do odczytu [`IAutoShapeLock`](/slides/python-net/pl/aspose.slides/iautoshapelock). |
| [`auto_shape_lock`](/slides/python-net/pl/aspose.slides/iautoshape/auto_shape_lock/) | Zwraca blokady AutoShape.<br/>            Tylko do odczytu [`IAutoShapeLock`](/slides/python-net/pl/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/pl/aspose.slides/iautoshape/text_frame/) | Zwraca obiekt TextFrame dla AutoShape.<br/>            Tylko do odczytu [`ITextFrame`](/slides/python-net/pl/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/pl/aspose.slides/iautoshape/use_background_fill/) | Określa, czy ten autoshape ma być wypełniony wypełnieniem tła slajdu zamiast określonego przez styl lub format wypełnienia.<br/>            Odczyt/zapis **bool**. |
| [`is_text_box`](/slides/python-net/pl/aspose.slides/iautoshape/is_text_box/) | Określa, czy kształt jest polem tekstowym. |
| [`shape_style`](/slides/python-net/pl/aspose.slides/iautoshape/shape_style/) |  |
| [`shape_type`](/slides/python-net/pl/aspose.slides/iautoshape/shape_type/) |  |
| [`adjustments`](/slides/python-net/pl/aspose.slides/iautoshape/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/pl/aspose.slides/iautoshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/pl/aspose.slides/iautoshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/pl/aspose.slides/iautoshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/pl/aspose.slides/iautoshape/raw_frame/) |  |
| [`frame`](/slides/python-net/pl/aspose.slides/iautoshape/frame/) |  |
| [`line_format`](/slides/python-net/pl/aspose.slides/iautoshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/pl/aspose.slides/iautoshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/pl/aspose.slides/iautoshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/pl/aspose.slides/iautoshape/fill_format/) |  |
| [`hidden`](/slides/python-net/pl/aspose.slides/iautoshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/pl/aspose.slides/iautoshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/pl/aspose.slides/iautoshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/pl/aspose.slides/iautoshape/rotation/) |  |
| [`x`](/slides/python-net/pl/aspose.slides/iautoshape/x/) |  |
| [`y`](/slides/python-net/pl/aspose.slides/iautoshape/y/) |  |
| [`width`](/slides/python-net/pl/aspose.slides/iautoshape/width/) |  |
| [`height`](/slides/python-net/pl/aspose.slides/iautoshape/height/) |  |
| [`alternative_text`](/slides/python-net/pl/aspose.slides/iautoshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/pl/aspose.slides/iautoshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/pl/aspose.slides/iautoshape/name/) |  |
| [`is_decorative`](/slides/python-net/pl/aspose.slides/iautoshape/is_decorative/) |  |
| [`unique_id`](/slides/python-net/pl/aspose.slides/iautoshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/pl/aspose.slides/iautoshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/pl/aspose.slides/iautoshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/pl/aspose.slides/iautoshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/pl/aspose.slides/iautoshape/parent_group/) |  |
| [`slide`](/slides/python-net/pl/aspose.slides/iautoshape/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides/iautoshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/pl/aspose.slides/iautoshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/pl/aspose.slides/iautoshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/pl/aspose.slides/iautoshape/hyperlink_manager/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_image(self)`](/slides/python-net/pl/aspose.slides/iautoshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/pl/aspose.slides/iautoshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/pl/aspose.slides/iautoshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/pl/aspose.slides/iautoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`add_text_frame(self, text)`](/slides/python-net/pl/aspose.slides/iautoshape/add_text_frame/#str) | Dodaje nowy TextFrame do kształtu.<br/>            Jeśli kształt już posiada TextFrame, po prostu zmienia jego tekst. |
| [`get_geometry_paths(self)`](/slides/python-net/pl/aspose.slides/iautoshape/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/pl/aspose.slides/iautoshape/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/pl/aspose.slides/iautoshape/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/pl/aspose.slides/iautoshape/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/pl/aspose.slides/iautoshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/pl/aspose.slides/iautoshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/pl/aspose.slides/iautoshape/get_base_placeholder/#) |  |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)