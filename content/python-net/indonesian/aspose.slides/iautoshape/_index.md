---
title: IAutoShape class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/iautoshape/
---
## IAutoShape kelas

Mewakili sebuah AutoShape.

Tipe IAutoShape mengekspos anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`shape_lock`](/slides/python-net/id/aspose.slides/iautoshape/shape_lock/) | Mengembalikan kunci shape.<br/>            Hanya-baca [`IAutoShapeLock`](/slides/python-net/id/aspose.slides/iautoshapelock). |
| [`auto_shape_lock`](/slides/python-net/id/aspose.slides/iautoshape/auto_shape_lock/) | Mengembalikan kunci AutoShape.<br/>            Hanya-baca [`IAutoShapeLock`](/slides/python-net/id/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/id/aspose.slides/iautoshape/text_frame/) | Mengembalikan objek TextFrame untuk AutoShape.<br/>            Hanya-baca [`ITextFrame`](/slides/python-net/id/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/id/aspose.slides/iautoshape/use_background_fill/) | Menentukan apakah autoshape ini harus diisi dengan latar belakang slide alih-alih yang ditentukan oleh gaya atau format isian.<br/>            Baca/tulis **bool**. |
| [`is_text_box`](/slides/python-net/id/aspose.slides/iautoshape/is_text_box/) | Menentukan apakah shape adalah kotak teks. |
| [`shape_style`](/slides/python-net/id/aspose.slides/iautoshape/shape_style/) |  |
| [`shape_type`](/slides/python-net/id/aspose.slides/iautoshape/shape_type/) |  |
| [`adjustments`](/slides/python-net/id/aspose.slides/iautoshape/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/id/aspose.slides/iautoshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/id/aspose.slides/iautoshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/id/aspose.slides/iautoshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/id/aspose.slides/iautoshape/raw_frame/) |  |
| [`frame`](/slides/python-net/id/aspose.slides/iautoshape/frame/) |  |
| [`line_format`](/slides/python-net/id/aspose.slides/iautoshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/id/aspose.slides/iautoshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/id/aspose.slides/iautoshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/id/aspose.slides/iautoshape/fill_format/) |  |
| [`hidden`](/slides/python-net/id/aspose.slides/iautoshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/id/aspose.slides/iautoshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/id/aspose.slides/iautoshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/id/aspose.slides/iautoshape/rotation/) |  |
| [`x`](/slides/python-net/id/aspose.slides/iautoshape/x/) |  |
| [`y`](/slides/python-net/id/aspose.slides/iautoshape/y/) |  |
| [`width`](/slides/python-net/id/aspose.slides/iautoshape/width/) |  |
| [`height`](/slides/python-net/id/aspose.slides/iautoshape/height/) |  |
| [`alternative_text`](/slides/python-net/id/aspose.slides/iautoshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/id/aspose.slides/iautoshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/id/aspose.slides/iautoshape/name/) |  |
| [`is_decorative`](/slides/python-net/id/aspose.slides/iautoshape/is_decorative/) |  |
| [`unique_id`](/slides/python-net/id/aspose.slides/iautoshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/id/aspose.slides/iautoshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/id/aspose.slides/iautoshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/id/aspose.slides/iautoshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/id/aspose.slides/iautoshape/parent_group/) |  |
| [`slide`](/slides/python-net/id/aspose.slides/iautoshape/slide/) |  |
| [`presentation`](/slides/python-net/id/aspose.slides/iautoshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/id/aspose.slides/iautoshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/id/aspose.slides/iautoshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/id/aspose.slides/iautoshape/hyperlink_manager/) |  |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`get_image(self)`](/slides/python-net/id/aspose.slides/iautoshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/id/aspose.slides/iautoshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/id/aspose.slides/iautoshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/id/aspose.slides/iautoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`add_text_frame(self, text)`](/slides/python-net/id/aspose.slides/iautoshape/add_text_frame/#str) | Menambahkan TextFrame baru ke sebuah shape.<br/>            Jika shape sudah memiliki TextFrame maka cukup mengubah teksnya. |
| [`get_geometry_paths(self)`](/slides/python-net/id/aspose.slides/iautoshape/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/id/aspose.slides/iautoshape/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/id/aspose.slides/iautoshape/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/id/aspose.slides/iautoshape/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/id/aspose.slides/iautoshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/id/aspose.slides/iautoshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/id/aspose.slides/iautoshape/get_base_placeholder/#) |  |


### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)