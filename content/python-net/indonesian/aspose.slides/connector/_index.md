---
title: Connector class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/connector/
---
## Connector kelas

Represents a connector.

**Inheritance:**[`Connector`](/slides/python-net/id/aspose.slides/connector) → [`GeometryShape`](/slides/python-net/id/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/id/aspose.slides/shape)

The Connector type exposes the following members:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`is_text_holder`](/slides/python-net/id/aspose.slides/connector/is_text_holder/) | Menentukan apakah shape adalah TextHolder_PPT.<br/>            Hanya-baca **bool**. |
| [`placeholder`](/slides/python-net/id/aspose.slides/connector/placeholder/) | Mengembalikan placeholder untuk sebuah shape. Mengembalikan None jika shape tidak memiliki placeholder.<br/>            Hanya-baca [`IPlaceholder`](/slides/python-net/id/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/id/aspose.slides/connector/custom_data/) | Mengembalikan data khusus shape.<br/>            Hanya-baca [`ICustomData`](/slides/python-net/id/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/id/aspose.slides/connector/raw_frame/) | Mengembalikan atau mengatur properti frame shape mentah.<br/>            Baca/tulis [`IShapeFrame`](/slides/python-net/id/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/id/aspose.slides/connector/frame/) | Mengembalikan atau mengatur properti frame shape.<br/>            Baca/tulis [`IShapeFrame`](/slides/python-net/id/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/id/aspose.slides/connector/line_format/) | Mengembalikan objek LineFormat yang berisi properti pemformatan garis untuk sebuah shape.<br/>            Catatan: dapat mengembalikan None untuk tipe shape tertentu yang tidak memiliki properti garis.<br/>            Hanya-baca [`ILineFormat`](/slides/python-net/id/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/id/aspose.slides/connector/three_d_format/) | Mengembalikan objek ThreeDFormat yang berisi properti efek 3d untuk sebuah shape.<br/>            Catatan: dapat mengembalikan None untuk tipe shape tertentu yang tidak memiliki properti 3d.<br/>            Hanya-baca [`IThreeDFormat`](/slides/python-net/id/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/id/aspose.slides/connector/effect_format/) | Mengembalikan objek EffectFormat yang berisi efek piksel yang diterapkan pada sebuah shape.<br/>            Catatan: dapat mengembalikan None untuk tipe shape tertentu yang tidak memiliki properti efek.<br/>            Hanya-baca [`IEffectFormat`](/slides/python-net/id/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/id/aspose.slides/connector/fill_format/) | Mengembalikan objek FillFormat yang berisi properti pemformatan isi untuk sebuah shape.<br/>            Catatan: dapat mengembalikan None untuk tipe shape tertentu yang tidak memiliki properti isi.<br/>            Hanya-baca [`IFillFormat`](/slides/python-net/id/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/id/aspose.slides/connector/hyperlink_click/) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse.<br/>            Baca/tulis [`IHyperlink`](/slides/python-net/id/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/id/aspose.slides/connector/hyperlink_mouse_over/) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk mouse over.<br/>            Baca/tulis [`IHyperlink`](/slides/python-net/id/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/id/aspose.slides/connector/hyperlink_manager/) | Mengembalikan manajer hyperlink.<br/>            Hanya-baca [`IHyperlinkManager`](/slides/python-net/id/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/id/aspose.slides/connector/hidden/) | Menentukan apakah shape disembunyikan.<br/>            Baca/tulis **bool**. |
| [`z_order_position`](/slides/python-net/id/aspose.slides/connector/z_order_position/) | Mengembalikan posisi sebuah shape dalam urutan-z.<br/>            Shapes[0] mengembalikan shape di bagian belakang urutan-z,<br/>            dan Shapes[Shapes.Count - 1] mengembalikan shape di bagian depan urutan-z.<br/>            Hanya-baca **int**. |
| [`connection_site_count`](/slides/python-net/id/aspose.slides/connector/connection_site_count/) | Mengembalikan jumlah situs koneksi pada shape.<br/>            Hanya-baca **int**. |
| [`rotation`](/slides/python-net/id/aspose.slides/connector/rotation/) | Mengembalikan atau mengatur jumlah derajat rotasi shape yang ditentukan sekitar<br/>            sumbu-z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif<br/>            menunjukkan rotasi berlawanan arah jarum jam.<br/>            Baca/tulis **float**. |
| [`x`](/slides/python-net/id/aspose.slides/connector/x/) | Mengambil atau mengatur koordinat x sudut kiri-atas shape, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`y`](/slides/python-net/id/aspose.slides/connector/y/) | Mengambil atau mengatur koordinat y sudut kiri-atas shape, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`width`](/slides/python-net/id/aspose.slides/connector/width/) | Mengambil atau mengatur lebar shape, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`height`](/slides/python-net/id/aspose.slides/connector/height/) | Mengambil atau mengatur tinggi shape, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`black_white_mode`](/slides/python-net/id/aspose.slides/connector/black_white_mode/) | Properti menentukan bagaimana shape akan dirender dalam mode tampilan hitam-putih..<br/>            Baca/tulis [`BlackWhiteMode`](/slides/python-net/id/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/id/aspose.slides/connector/unique_id/) | Mengembalikan pengidentifikasi internal yang berskala presentasi yang ditujukan untuk digunakan oleh add-in atau kode lainnya.<br/>            Karena nilai ini dapat dialokasikan ulang oleh pengguna atau secara programatis, nilai ini tidak boleh diperlakukan<br/>            sebagai kunci unik yang persisten.<br/>            Hanya-baca **int**.<br/>            Lihat juga [`Shape.office_interop_shape_id`](/slides/python-net/id/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/id/aspose.slides/connector/office_interop_shape_id/) | Mengembalikan pengidentifikasi unik berskala slide yang tetap konstan selama masa hidup shape dan<br/>            memungkinkan PowerPoint atau kode interop mereferensikan shape secara andal dari mana saja dalam dokumen.<br/>            Hanya-baca **int**.<br/>            Lihat juga [`Shape.unique_id`](/slides/python-net/id/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/id/aspose.slides/connector/alternative_text/) | Mengembalikan atau mengatur teks alternatif yang terkait dengan shape.<br/>            Baca/tulis **str**. |
| [`alternative_text_title`](/slides/python-net/id/aspose.slides/connector/alternative_text_title/) | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan shape.<br/>            Baca/tulis **str**. |
| [`name`](/slides/python-net/id/aspose.slides/connector/name/) | Mengembalikan atau mengatur nama shape.<br/>            Harus tidak None. Gunakan nilai string kosong jika diperlukan.<br/>            Baca/tulis **str**. |
| [`is_decorative`](/slides/python-net/id/aspose.slides/connector/is_decorative/) | Mengambil atau mengatur opsi 'Mark as decorative'<br/>            Baca/tulis **bool**. |
| [`shape_lock`](/slides/python-net/id/aspose.slides/connector/shape_lock/) | Mengembalikan kunci shape.<br/>            Hanya-baca [`IConnectorLock`](/slides/python-net/id/aspose.slides/iconnectorlock). |
| [`is_grouped`](/slides/python-net/id/aspose.slides/connector/is_grouped/) | Menentukan apakah shape dikelompokkan.<br/>            Hanya-baca **bool**. |
| [`parent_group`](/slides/python-net/id/aspose.slides/connector/parent_group/) | Mengembalikan objek GroupShape induk jika shape dikelompokkan. Jika tidak, mengembalikan None.<br/>            Hanya-baca [`IGroupShape`](/slides/python-net/id/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/id/aspose.slides/connector/slide/) | Mengembalikan slide induk dari sebuah shape.<br/>            Hanya-baca [`IBaseSlide`](/slides/python-net/id/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/id/aspose.slides/connector/presentation/) | Mengembalikan presentasi induk dari sebuah slide.<br/>            Hanya-baca [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/id/aspose.slides/connector/shape_style/) | Mengembalikan objek gaya shape.<br/>            Hanya-baca [`IShapeStyle`](/slides/python-net/id/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/id/aspose.slides/connector/shape_type/) | Mengembalikan atau mengatur tipe AutoShape.<br/>            Baca/tulis [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/id/aspose.slides/connector/adjustments/) | Mengembalikan koleksi nilai penyesuaian shape.<br/>            Hanya-baca [`IAdjustValueCollection`](/slides/python-net/id/aspose.slides/iadjustvaluecollection). |
| [`connector_lock`](/slides/python-net/id/aspose.slides/connector/connector_lock/) | Mengembalikan kunci connector.<br/>            Hanya-baca [`IConnectorLock`](/slides/python-net/id/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/id/aspose.slides/connector/start_shape_connected_to/) | Mengembalikan atau mengatur shape yang akan menjadi titik awal konektor.<br/>            Baca/tulis [`IShape`](/slides/python-net/id/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/id/aspose.slides/connector/end_shape_connected_to/) | Mengembalikan atau mengatur shape yang akan menjadi titik akhir konektor.<br/>            Baca/tulis [`IShape`](/slides/python-net/id/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/id/aspose.slides/connector/start_shape_connection_site_index/) | Mengembalikan atau mengatur indeks situs koneksi untuk shape awal.<br/>            Baca/tulis **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/id/aspose.slides/connector/end_shape_connection_site_index/) | Mengembalikan atau mengatur indeks situs koneksi untuk shape akhir.<br/>            Baca/tulis **int**. |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`get_image(self)`](/slides/python-net/id/aspose.slides/connector/get_image/#) | Mengembalikan thumbnail shape.<br/>            Tipe ShapeThumbnailBounds.Shape digunakan secara default untuk batas thumbnail shape. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/id/aspose.slides/connector/get_image/#shapethumbnailbounds-float-float) | Mengembalikan thumbnail shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/id/aspose.slides/connector/write_as_svg/#iorawiobase) | Menyimpan konten Shape sebagai berkas SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/id/aspose.slides/connector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Menyimpan konten Shape sebagai berkas SVG. |
| [`remove_placeholder(self)`](/slides/python-net/id/aspose.slides/connector/remove_placeholder/#) | Mendefinisikan bahwa shape ini bukan placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/id/aspose.slides/connector/add_placeholder/#iplaceholder) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [`get_base_placeholder(self)`](/slides/python-net/id/aspose.slides/connector/get_base_placeholder/#) | Mengembalikan shape placeholder dasar (shape dari layout dan/atau master slide yang diwarisi oleh shape saat ini).<br/>            Mengembalikan None jika shape saat ini tidak diwarisi. |
| [`get_visual_bounds(self)`](/slides/python-net/id/aspose.slides/connector/get_visual_bounds/#) | Mengambil batas visual shape yang dihitung dari konten yang dirender. |
| [`get_geometry_paths(self)`](/slides/python-net/id/aspose.slides/connector/get_geometry_paths/#) | Mengembalikan salinan jalur shape geometri. Koordinat relatif terhadap sudut kiri-atas shape. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/id/aspose.slides/connector/set_geometry_path/#igeometrypath) | Memperbarui geometri shape dari objek [`IGeometryPath`](/slides/python-net/id/aspose.slides/igeometrypath). Koordinat harus relatif terhadap sudut kiri<br/>             atas shape.<br/>             Mengubah tipe shape ([`GeometryShape.shape_type`](/slides/python-net/id/aspose.slides/geometryshape/shape_type)) menjadi [`ShapeType.CUSTOM`](/slides/python-net/id/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/id/aspose.slides/connector/set_geometry_paths/#listigeometrypath) | Memperbarui geometri shape dari array [`IGeometryPath`](/slides/python-net/id/aspose.slides/igeometrypath). Koordinat harus relatif terhadap sudut kiri<br/>             atas shape.<br/>             Mengubah tipe shape ([`GeometryShape.shape_type`](/slides/python-net/id/aspose.slides/geometryshape/shape_type)) menjadi [`ShapeType.CUSTOM`](/slides/python-net/id/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/id/aspose.slides/connector/create_shape_elements/#) | Membuat dan mengembalikan array elemen shape. |
| [`reroute(self)`](/slides/python-net/id/aspose.slides/connector/reroute/#) | Mengalihkan jalur connector sehingga mengambil jalur terpendek yang memungkinkan antara shape yang dihubungkannya. |

### Lihat Juga
* kelas [`Connector`](/slides/python-net/id/aspose.slides/connector)
* kelas [`GeometryShape`](/slides/python-net/id/aspose.slides/geometryshape)
* kelas [`Shape`](/slides/python-net/id/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)