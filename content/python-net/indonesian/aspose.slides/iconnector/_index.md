---
title: IConnector class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/iconnector/
---
## Kelas IConnector

Mewakili sebuah konektor.

Tipe IConnector mengekspos anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`shape_lock`](/slides/python-net/id/aspose.slides/iconnector/shape_lock/) | Mengembalikan kunci shape.<br/>            Baca-saja [`IConnectorLock`](/slides/python-net/id/aspose.slides/iconnectorlock). |
| [`connector_lock`](/slides/python-net/id/aspose.slides/iconnector/connector_lock/) | Mengembalikan kunci Connector.<br/>            Baca-saja [`IConnectorLock`](/slides/python-net/id/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/id/aspose.slides/iconnector/start_shape_connected_to/) | Mengembalikan atau mengatur shape untuk menempelkan awal konektor.<br/>            Baca/tulis [`IShape`](/slides/python-net/id/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/id/aspose.slides/iconnector/end_shape_connected_to/) | Mengembalikan atau mengatur shape untuk menempelkan akhir konektor.<br/>            Baca/tulis [`IShape`](/slides/python-net/id/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/id/aspose.slides/iconnector/start_shape_connection_site_index/) | Mengembalikan atau mengatur indeks situs koneksi untuk shape awal.<br/>            Baca/tulis **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/id/aspose.slides/iconnector/end_shape_connection_site_index/) | Mengembalikan atau mengatur indeks situs koneksi untuk shape akhir.<br/>            Baca/tulis **int**. |
| [`shape_style`](/slides/python-net/id/aspose.slides/iconnector/shape_style/) |  |
| [`shape_type`](/slides/python-net/id/aspose.slides/iconnector/shape_type/) |  |
| [`adjustments`](/slides/python-net/id/aspose.slides/iconnector/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/id/aspose.slides/iconnector/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/id/aspose.slides/iconnector/placeholder/) |  |
| [`custom_data`](/slides/python-net/id/aspose.slides/iconnector/custom_data/) |  |
| [`raw_frame`](/slides/python-net/id/aspose.slides/iconnector/raw_frame/) |  |
| [`frame`](/slides/python-net/id/aspose.slides/iconnector/frame/) |  |
| [`line_format`](/slides/python-net/id/aspose.slides/iconnector/line_format/) |  |
| [`three_d_format`](/slides/python-net/id/aspose.slides/iconnector/three_d_format/) |  |
| [`effect_format`](/slides/python-net/id/aspose.slides/iconnector/effect_format/) |  |
| [`fill_format`](/slides/python-net/id/aspose.slides/iconnector/fill_format/) |  |
| [`hidden`](/slides/python-net/id/aspose.slides/iconnector/hidden/) |  |
| [`z_order_position`](/slides/python-net/id/aspose.slides/iconnector/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/id/aspose.slides/iconnector/connection_site_count/) |  |
| [`rotation`](/slides/python-net/id/aspose.slides/iconnector/rotation/) |  |
| [`x`](/slides/python-net/id/aspose.slides/iconnector/x/) |  |
| [`y`](/slides/python-net/id/aspose.slides/iconnector/y/) |  |
| [`width`](/slides/python-net/id/aspose.slides/iconnector/width/) |  |
| [`height`](/slides/python-net/id/aspose.slides/iconnector/height/) |  |
| [`alternative_text`](/slides/python-net/id/aspose.slides/iconnector/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/id/aspose.slides/iconnector/alternative_text_title/) |  |
| [`name`](/slides/python-net/id/aspose.slides/iconnector/name/) |  |
| [`is_decorative`](/slides/python-net/id/aspose.slides/iconnector/is_decorative/) |  |
| [`unique_id`](/slides/python-net/id/aspose.slides/iconnector/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/id/aspose.slides/iconnector/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/id/aspose.slides/iconnector/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/id/aspose.slides/iconnector/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/id/aspose.slides/iconnector/parent_group/) |  |
| [`slide`](/slides/python-net/id/aspose.slides/iconnector/slide/) |  |
| [`presentation`](/slides/python-net/id/aspose.slides/iconnector/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/id/aspose.slides/iconnector/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/id/aspose.slides/iconnector/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/id/aspose.slides/iconnector/hyperlink_manager/) |  |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`get_image(self)`](/slides/python-net/id/aspose.slides/iconnector/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/id/aspose.slides/iconnector/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/id/aspose.slides/iconnector/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/id/aspose.slides/iconnector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`reroute(self)`](/slides/python-net/id/aspose.slides/iconnector/reroute/#) | Mengarahkan ulang konektor sehingga mengambil jalur terpendek antara shape yang dihubungkannya. |
| [`get_geometry_paths(self)`](/slides/python-net/id/aspose.slides/iconnector/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/id/aspose.slides/iconnector/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/id/aspose.slides/iconnector/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/id/aspose.slides/iconnector/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/id/aspose.slides/iconnector/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/id/aspose.slides/iconnector/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/id/aspose.slides/iconnector/get_base_placeholder/#) |  |

### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)