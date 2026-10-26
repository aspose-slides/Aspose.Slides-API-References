---
title: IGeometryShape class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/igeometryshape/
---
## IGeometryShape kelas

Mewakili kelas induk untuk semua shape geometris.

Tipe IGeometryShape mengekspos anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`shape_style`](/slides/python-net/id/aspose.slides/igeometryshape/shape_style/) | Mengembalikan objek gaya shape.<br/>            Hanya-baca [`IShapeStyle`](/slides/python-net/id/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/id/aspose.slides/igeometryshape/shape_type/) | Mengembalikan atau mengatur tipe preset geometri.<br/>            Catatan: saat nilai berubah semua nilai penyesuaian akan direset ke nilai default.<br/>            Baca/tulis [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/id/aspose.slides/igeometryshape/adjustments/) | Mengembalikan koleksi nilai penyesuaian shape.<br/>            Hanya-baca [`IAdjustValueCollection`](/slides/python-net/id/aspose.slides/iadjustvaluecollection). |
| [`is_text_holder`](/slides/python-net/id/aspose.slides/igeometryshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/id/aspose.slides/igeometryshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/id/aspose.slides/igeometryshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/id/aspose.slides/igeometryshape/raw_frame/) |  |
| [`frame`](/slides/python-net/id/aspose.slides/igeometryshape/frame/) |  |
| [`line_format`](/slides/python-net/id/aspose.slides/igeometryshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/id/aspose.slides/igeometryshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/id/aspose.slides/igeometryshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/id/aspose.slides/igeometryshape/fill_format/) |  |
| [`hidden`](/slides/python-net/id/aspose.slides/igeometryshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/id/aspose.slides/igeometryshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/id/aspose.slides/igeometryshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/id/aspose.slides/igeometryshape/rotation/) |  |
| [`x`](/slides/python-net/id/aspose.slides/igeometryshape/x/) |  |
| [`y`](/slides/python-net/id/aspose.slides/igeometryshape/y/) |  |
| [`width`](/slides/python-net/id/aspose.slides/igeometryshape/width/) |  |
| [`height`](/slides/python-net/id/aspose.slides/igeometryshape/height/) |  |
| [`alternative_text`](/slides/python-net/id/aspose.slides/igeometryshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/id/aspose.slides/igeometryshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/id/aspose.slides/igeometryshape/name/) |  |
| [`is_decorative`](/slides/python-net/id/aspose.slides/igeometryshape/is_decorative/) |  |
| [`shape_lock`](/slides/python-net/id/aspose.slides/igeometryshape/shape_lock/) |  |
| [`unique_id`](/slides/python-net/id/aspose.slides/igeometryshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/id/aspose.slides/igeometryshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/id/aspose.slides/igeometryshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/id/aspose.slides/igeometryshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/id/aspose.slides/igeometryshape/parent_group/) |  |
| [`slide`](/slides/python-net/id/aspose.slides/igeometryshape/slide/) |  |
| [`presentation`](/slides/python-net/id/aspose.slides/igeometryshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/id/aspose.slides/igeometryshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/id/aspose.slides/igeometryshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/id/aspose.slides/igeometryshape/hyperlink_manager/) |  |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`get_image(self)`](/slides/python-net/id/aspose.slides/igeometryshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/id/aspose.slides/igeometryshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/id/aspose.slides/igeometryshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/id/aspose.slides/igeometryshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`get_geometry_paths(self)`](/slides/python-net/id/aspose.slides/igeometryshape/get_geometry_paths/#) | Mengembalikan salinan jalur dari shape geometri. Koordinat relatif terhadap sudut kiri atas shape. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/id/aspose.slides/igeometryshape/set_geometry_path/#igeometrypath) | Memperbarui geometri shape dari objek [`IGeometryPath`](/slides/python-net/id/aspose.slides/igeometrypath). Koordinat harus relatif terhadap kiri<br/>             sudut atas shape.<br/>             Mengubah tipe shape ([`IGeometryShape.shape_type`](/slides/python-net/id/aspose.slides/igeometryshape/shape_type)) menjadi [`ShapeType.CUSTOM`](/slides/python-net/id/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/id/aspose.slides/igeometryshape/set_geometry_paths/#listigeometrypath) | Memperbarui geometri shape dari array [`IGeometryPath`](/slides/python-net/id/aspose.slides/igeometrypath). Koordinat harus relatif terhadap kiri<br/>             sudut atas shape.<br/>             Mengubah tipe shape ([`IGeometryShape.shape_type`](/slides/python-net/id/aspose.slides/igeometryshape/shape_type)) menjadi [`ShapeType.CUSTOM`](/slides/python-net/id/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/id/aspose.slides/igeometryshape/create_shape_elements/#) | Membuat dan mengembalikan array elemen shape. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/id/aspose.slides/igeometryshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/id/aspose.slides/igeometryshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/id/aspose.slides/igeometryshape/get_base_placeholder/#) |  |

### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)