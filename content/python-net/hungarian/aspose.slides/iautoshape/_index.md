---
title: IAutoShape class
second_title: Aspose.Slides Python számára .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides/iautoshape/
---
## IAutoShape osztály

Az AutoShape-t képviseli.

Az IAutoShape típus a következő tagokat tartalmazza:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`shape_lock`](/slides/python-net/hu/aspose.slides/iautoshape/shape_lock/) | Visszaadja az alakzat zárolásait.<br/>            Csak olvasható [`IAutoShapeLock`](/slides/python-net/hu/aspose.slides/iautoshapelock). |
| [`auto_shape_lock`](/slides/python-net/hu/aspose.slides/iautoshape/auto_shape_lock/) | Visszaadja az AutoShape zárolásait.<br/>            Csak olvasható [`IAutoShapeLock`](/slides/python-net/hu/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/hu/aspose.slides/iautoshape/text_frame/) | Visszaadja az AutoShape TextFrame objektumát.<br/>            Csak olvasható [`ITextFrame`](/slides/python-net/hu/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/hu/aspose.slides/iautoshape/use_background_fill/) | Meghatározza, hogy ez az autoshape a dia háttérkitöltésével legyen-e kitöltve a stílus vagy a kitöltési formátum által meghatározott helyett.<br/>            Olvasható/írható **bool**. |
| [`is_text_box`](/slides/python-net/hu/aspose.slides/iautoshape/is_text_box/) | Megadja, hogy az alakzat szövegdoboz-e. |
| [`shape_style`](/slides/python-net/hu/aspose.slides/iautoshape/shape_style/) |  |
| [`shape_type`](/slides/python-net/hu/aspose.slides/iautoshape/shape_type/) |  |
| [`adjustments`](/slides/python-net/hu/aspose.slides/iautoshape/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/hu/aspose.slides/iautoshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/hu/aspose.slides/iautoshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/hu/aspose.slides/iautoshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/hu/aspose.slides/iautoshape/raw_frame/) |  |
| [`frame`](/slides/python-net/hu/aspose.slides/iautoshape/frame/) |  |
| [`line_format`](/slides/python-net/hu/aspose.slides/iautoshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/hu/aspose.slides/iautoshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/hu/aspose.slides/iautoshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/hu/aspose.slides/iautoshape/fill_format/) |  |
| [`hidden`](/slides/python-net/hu/aspose.slides/iautoshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/hu/aspose.slides/iautoshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/hu/aspose.slides/iautoshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/hu/aspose.slides/iautoshape/rotation/) |  |
| [`x`](/slides/python-net/hu/aspose.slides/iautoshape/x/) |  |
| [`y`](/slides/python-net/hu/aspose.slides/iautoshape/y/) |  |
| [`width`](/slides/python-net/hu/aspose.slides/iautoshape/width/) |  |
| [`height`](/slides/python-net/hu/aspose.slides/iautoshape/height/) |  |
| [`alternative_text`](/slides/python-net/hu/aspose.slides/iautoshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/hu/aspose.slides/iautoshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/hu/aspose.slides/iautoshape/name/) |  |
| [`is_decorative`](/slides/python-net/hu/aspose.slides/iautoshape/is_decorative/) |  |
| [`unique_id`](/slides/python-net/hu/aspose.slides/iautoshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/hu/aspose.slides/iautoshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/hu/aspose.slides/iautoshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/hu/aspose.slides/iautoshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/hu/aspose.slides/iautoshape/parent_group/) |  |
| [`slide`](/slides/python-net/hu/aspose.slides/iautoshape/slide/) |  |
| [`presentation`](/slides/python-net/hu/aspose.slides/iautoshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/hu/aspose.slides/iautoshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/hu/aspose.slides/iautoshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/hu/aspose.slides/iautoshape/hyperlink_manager/) |  |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`get_image(self)`](/slides/python-net/hu/aspose.slides/iautoshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/iautoshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/hu/aspose.slides/iautoshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hu/aspose.slides/iautoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`add_text_frame(self, text)`](/slides/python-net/hu/aspose.slides/iautoshape/add_text_frame/#str) | Új TextFrame-et ad hozzá egy alakzathoz.<br/>            Ha az alakzat már rendelkezik TextFrame-el, akkor egyszerűen módosítja a szövegét. |
| [`get_geometry_paths(self)`](/slides/python-net/hu/aspose.slides/iautoshape/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/hu/aspose.slides/iautoshape/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/hu/aspose.slides/iautoshape/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/hu/aspose.slides/iautoshape/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/hu/aspose.slides/iautoshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/hu/aspose.slides/iautoshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/hu/aspose.slides/iautoshape/get_base_placeholder/#) |  |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)