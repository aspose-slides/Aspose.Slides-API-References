---
title: IAutoShape class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/iautoshape/
---
## IAutoShape klass

Representerar en AutoShape.

Typen IAutoShape exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`shape_lock`](/slides/python-net/sv/aspose.slides/iautoshape/shape_lock/) | Returnerar formens lås.<br/>            Skrivskyddad [`IAutoShapeLock`](/slides/python-net/sv/aspose.slides/iautoshapelock). |
| [`auto_shape_lock`](/slides/python-net/sv/aspose.slides/iautoshape/auto_shape_lock/) | Returnerar AutoShape:s lås.<br/>            Skrivskyddad [`IAutoShapeLock`](/slides/python-net/sv/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/sv/aspose.slides/iautoshape/text_frame/) | Returnerar TextFrame-objekt för AutoShape.<br/>            Skrivskyddad [`ITextFrame`](/slides/python-net/sv/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/sv/aspose.slides/iautoshape/use_background_fill/) | Bestämmer om denna autoshape ska fyllas med slidens bakgrundsfyllning istället för specificerad av stil eller fyllningsformat.<br/>            Läs/skriv **bool**. |
| [`is_text_box`](/slides/python-net/sv/aspose.slides/iautoshape/is_text_box/) | Anger om formen är en textruta. |
| [`shape_style`](/slides/python-net/sv/aspose.slides/iautoshape/shape_style/) |  |
| [`shape_type`](/slides/python-net/sv/aspose.slides/iautoshape/shape_type/) |  |
| [`adjustments`](/slides/python-net/sv/aspose.slides/iautoshape/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/sv/aspose.slides/iautoshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/sv/aspose.slides/iautoshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/sv/aspose.slides/iautoshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/sv/aspose.slides/iautoshape/raw_frame/) |  |
| [`frame`](/slides/python-net/sv/aspose.slides/iautoshape/frame/) |  |
| [`line_format`](/slides/python-net/sv/aspose.slides/iautoshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/sv/aspose.slides/iautoshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/sv/aspose.slides/iautoshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/sv/aspose.slides/iautoshape/fill_format/) |  |
| [`hidden`](/slides/python-net/sv/aspose.slides/iautoshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/sv/aspose.slides/iautoshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/sv/aspose.slides/iautoshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/sv/aspose.slides/iautoshape/rotation/) |  |
| [`x`](/slides/python-net/sv/aspose.slides/iautoshape/x/) |  |
| [`y`](/slides/python-net/sv/aspose.slides/iautoshape/y/) |  |
| [`width`](/slides/python-net/sv/aspose.slides/iautoshape/width/) |  |
| [`height`](/slides/python-net/sv/aspose.slides/iautoshape/height/) |  |
| [`alternative_text`](/slides/python-net/sv/aspose.slides/iautoshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/sv/aspose.slides/iautoshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/sv/aspose.slides/iautoshape/name/) |  |
| [`is_decorative`](/slides/python-net/sv/aspose.slides/iautoshape/is_decorative/) |  |
| [`unique_id`](/slides/python-net/sv/aspose.slides/iautoshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/sv/aspose.slides/iautoshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/sv/aspose.slides/iautoshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/sv/aspose.slides/iautoshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/sv/aspose.slides/iautoshape/parent_group/) |  |
| [`slide`](/slides/python-net/sv/aspose.slides/iautoshape/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides/iautoshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/sv/aspose.slides/iautoshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/sv/aspose.slides/iautoshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/sv/aspose.slides/iautoshape/hyperlink_manager/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_image(self)`](/slides/python-net/sv/aspose.slides/iautoshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides/iautoshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/sv/aspose.slides/iautoshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/sv/aspose.slides/iautoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`add_text_frame(self, text)`](/slides/python-net/sv/aspose.slides/iautoshape/add_text_frame/#str) | Lägger till en ny TextFrame till en form.<br/>            Om formen redan har TextFrame ändras bara dess text. |
| [`get_geometry_paths(self)`](/slides/python-net/sv/aspose.slides/iautoshape/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/sv/aspose.slides/iautoshape/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/sv/aspose.slides/iautoshape/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/sv/aspose.slides/iautoshape/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/sv/aspose.slides/iautoshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/sv/aspose.slides/iautoshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/sv/aspose.slides/iautoshape/get_base_placeholder/#) |  |


### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)