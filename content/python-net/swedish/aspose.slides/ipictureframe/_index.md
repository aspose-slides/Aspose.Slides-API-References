---
title: IPictureFrame class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ipictureframe/
---
## IPictureFrame klass

Representerar en ram med en bild inuti.

IPictureFrame-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`shape_lock`](/slides/python-net/sv/aspose.slides/ipictureframe/shape_lock/) | Returnerar formens lås.<br/>            Skrivskyddad [`IPictureFrameLock`](/slides/python-net/sv/aspose.slides/ipictureframelock). |
| [`picture_frame_lock`](/slides/python-net/sv/aspose.slides/ipictureframe/picture_frame_lock/) | Returnerar PictureFrames lås.<br/>            Skrivskyddad [`IPictureFrameLock`](/slides/python-net/sv/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/sv/aspose.slides/ipictureframe/picture_format/) | Returnerar PictureFillFormat-objektet för en bildram.<br/>            Skrivskyddad [`IPictureFillFormat`](/slides/python-net/sv/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/sv/aspose.slides/ipictureframe/relative_scale_height/) | Returnerar eller anger skalning av höjden (relativt originalbildens storlek) för bildramen. Värde 1.0 motsvarar 100%.<br/>            Läs/skriv **float**. |
| [`relative_scale_width`](/slides/python-net/sv/aspose.slides/ipictureframe/relative_scale_width/) | Returnerar eller anger skalning av bredden (relativt originalbildens storlek) för bildramen. Värde 1.0 motsvarar 100%.<br/>            Läs/skriv **float**. |
| [`shape_style`](/slides/python-net/sv/aspose.slides/ipictureframe/shape_style/) |  |
| [`shape_type`](/slides/python-net/sv/aspose.slides/ipictureframe/shape_type/) |  |
| [`adjustments`](/slides/python-net/sv/aspose.slides/ipictureframe/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/sv/aspose.slides/ipictureframe/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/sv/aspose.slides/ipictureframe/placeholder/) |  |
| [`custom_data`](/slides/python-net/sv/aspose.slides/ipictureframe/custom_data/) |  |
| [`raw_frame`](/slides/python-net/sv/aspose.slides/ipictureframe/raw_frame/) |  |
| [`frame`](/slides/python-net/sv/aspose.slides/ipictureframe/frame/) |  |
| [`line_format`](/slides/python-net/sv/aspose.slides/ipictureframe/line_format/) |  |
| [`three_d_format`](/slides/python-net/sv/aspose.slides/ipictureframe/three_d_format/) |  |
| [`effect_format`](/slides/python-net/sv/aspose.slides/ipictureframe/effect_format/) |  |
| [`fill_format`](/slides/python-net/sv/aspose.slides/ipictureframe/fill_format/) |  |
| [`hidden`](/slides/python-net/sv/aspose.slides/ipictureframe/hidden/) |  |
| [`z_order_position`](/slides/python-net/sv/aspose.slides/ipictureframe/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/sv/aspose.slides/ipictureframe/connection_site_count/) |  |
| [`rotation`](/slides/python-net/sv/aspose.slides/ipictureframe/rotation/) |  |
| [`x`](/slides/python-net/sv/aspose.slides/ipictureframe/x/) |  |
| [`y`](/slides/python-net/sv/aspose.slides/ipictureframe/y/) |  |
| [`width`](/slides/python-net/sv/aspose.slides/ipictureframe/width/) |  |
| [`height`](/slides/python-net/sv/aspose.slides/ipictureframe/height/) |  |
| [`alternative_text`](/slides/python-net/sv/aspose.slides/ipictureframe/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/sv/aspose.slides/ipictureframe/alternative_text_title/) |  |
| [`name`](/slides/python-net/sv/aspose.slides/ipictureframe/name/) |  |
| [`is_decorative`](/slides/python-net/sv/aspose.slides/ipictureframe/is_decorative/) |  |
| [`unique_id`](/slides/python-net/sv/aspose.slides/ipictureframe/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/sv/aspose.slides/ipictureframe/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/sv/aspose.slides/ipictureframe/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/sv/aspose.slides/ipictureframe/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/sv/aspose.slides/ipictureframe/parent_group/) |  |
| [`slide`](/slides/python-net/sv/aspose.slides/ipictureframe/slide/) |  |
| [`presentation`](/slides/python-net/sv/aspose.slides/ipictureframe/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/sv/aspose.slides/ipictureframe/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/sv/aspose.slides/ipictureframe/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/sv/aspose.slides/ipictureframe/hyperlink_manager/) |  |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_image(self)`](/slides/python-net/sv/aspose.slides/ipictureframe/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/sv/aspose.slides/ipictureframe/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/sv/aspose.slides/ipictureframe/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/sv/aspose.slides/ipictureframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/sv/aspose.slides/ipictureframe/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/sv/aspose.slides/ipictureframe/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/sv/aspose.slides/ipictureframe/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/sv/aspose.slides/ipictureframe/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/sv/aspose.slides/ipictureframe/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/sv/aspose.slides/ipictureframe/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/sv/aspose.slides/ipictureframe/get_base_placeholder/#) |  |

### Se också
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)