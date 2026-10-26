---
title: AutoShape class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/autoshape/
---
## Kelas AutoShape

Mewakili sebuah AutoShape.

**Inheritance:**[`AutoShape`](/slides/python-net/id/aspose.slides/autoshape) → [`GeometryShape`](/slides/python-net/id/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/id/aspose.slides/shape)

Tipe AutoShape menampilkan anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`is_text_holder`](/slides/python-net/id/aspose.slides/autoshape/is_text_holder/) | Menentukan apakah bentuk adalah TextHolder_PPT.<br/>            Baca-saja **bool**. |
| [`placeholder`](/slides/python-net/id/aspose.slides/autoshape/placeholder/) | Mengembalikan placeholder untuk sebuah bentuk. Mengembalikan None jika bentuk tidak memiliki placeholder.<br/>            Baca-saja [`IPlaceholder`](/slides/python-net/id/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/id/aspose.slides/autoshape/custom_data/) | Mengembalikan data khusus bentuk.<br/>            Baca-saja [`ICustomData`](/slides/python-net/id/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/id/aspose.slides/autoshape/raw_frame/) | Mengembalikan atau mengatur properti frame bentuk mentah.<br/>            Baca/tulis [`IShapeFrame`](/slides/python-net/id/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/id/aspose.slides/autoshape/frame/) | Mengembalikan atau mengatur properti frame bentuk.<br/>            Baca/tulis [`IShapeFrame`](/slides/python-net/id/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/id/aspose.slides/autoshape/line_format/) | Mengembalikan objek LineFormat yang berisi properti pemformatan garis untuk sebuah bentuk.<br/>            Catatan: dapat mengembalikan None untuk tipe bentuk tertentu yang tidak memiliki properti garis.<br/>            Baca-saja [`ILineFormat`](/slides/python-net/id/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/id/aspose.slides/autoshape/three_d_format/) | Mengembalikan objek ThreeDFormat yang berisi properti efek 3d untuk sebuah bentuk.<br/>            Catatan: dapat mengembalikan None untuk tipe bentuk tertentu yang tidak memiliki properti 3d.<br/>            Baca-saja [`IThreeDFormat`](/slides/python-net/id/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/id/aspose.slides/autoshape/effect_format/) | Mengembalikan objek EffectFormat yang berisi efek piksel yang diterapkan pada sebuah bentuk.<br/>            Catatan: dapat mengembalikan None untuk tipe bentuk tertentu yang tidak memiliki properti efek.<br/>            Baca-saja [`IEffectFormat`](/slides/python-net/id/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/id/aspose.slides/autoshape/fill_format/) | Mengembalikan objek FillFormat yang berisi properti pemformatan isi untuk sebuah bentuk.<br/>            Catatan: dapat mengembalikan None untuk tipe bentuk tertentu yang tidak memiliki properti isi.<br/>            Baca-saja [`IFillFormat`](/slides/python-net/id/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/id/aspose.slides/autoshape/hyperlink_click/) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse.<br/>            Baca/tulis [`IHyperlink`](/slides/python-net/id/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/id/aspose.slides/autoshape/hyperlink_mouse_over/) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk hover mouse.<br/>            Baca/tulis [`IHyperlink`](/slides/python-net/id/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/id/aspose.slides/autoshape/hyperlink_manager/) | Mengembalikan manajer hyperlink.<br/>            Baca-saja [`IHyperlinkManager`](/slides/python-net/id/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/id/aspose.slides/autoshape/hidden/) | Menentukan apakah bentuk tersembunyi.<br/>            Baca/tulis **bool**. |
| [`z_order_position`](/slides/python-net/id/aspose.slides/autoshape/z_order_position/) | Mengembalikan posisi sebuah bentuk dalam urutan z.<br/>            Shapes[0] mengembalikan bentuk di belakang urutan z,<br/>            dan Shapes[Shapes.Count - 1] mengembalikan bentuk di depan urutan z.<br/>            Baca-saja **int**. |
| [`connection_site_count`](/slides/python-net/id/aspose.slides/autoshape/connection_site_count/) | Mengembalikan jumlah titik koneksi pada bentuk.<br/>            Baca-saja **int**. |
| [`rotation`](/slides/python-net/id/aspose.slides/autoshape/rotation/) | Mengembalikan atau mengatur jumlah derajat rotasi bentuk yang ditentukan di sekitar sumbu z.<br/>            Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif<br/>            menunjukkan rotasi berlawanan arah jarum jam.<br/>            Baca/tulis **float**. |
| [`x`](/slides/python-net/id/aspose.slides/autoshape/x/) | Mendapatkan atau mengatur koordinat x sudut kiri atas bentuk, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`y`](/slides/python-net/id/aspose.slides/autoshape/y/) | Mendapatkan atau mengatur koordinat y sudut kiri atas bentuk, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`width`](/slides/python-net/id/aspose.slides/autoshape/width/) | Mendapatkan atau mengatur lebar bentuk, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`height`](/slides/python-net/id/aspose.slides/autoshape/height/) | Mendapatkan atau mengatur tinggi bentuk, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`black_white_mode`](/slides/python-net/id/aspose.slides/autoshape/black_white_mode/) | Properti menentukan bagaimana bentuk akan ditampilkan dalam mode hitam-putih..<br/>            Baca/tulis [`BlackWhiteMode`](/slides/python-net/id/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/id/aspose.slides/autoshape/unique_id/) | Mengembalikan pengidentifikasi internal yang berskala presentasi yang dimaksudkan untuk penggunaan oleh add-in atau kode lain.<br/>            Karena nilai ini dapat ditetapkan ulang oleh pengguna atau secara programatik, tidak boleh diperlakukan<br/>            sebagai kunci unik yang persisten.<br/>            Baca-saja **int**.<br/>            Lihat juga [`Shape.office_interop_shape_id`](/slides/python-net/id/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/id/aspose.slides/autoshape/office_interop_shape_id/) | Mengembalikan pengidentifikasi unik berskala slide yang tetap konstan selama masa hidup bentuk dan<br/>            memungkinkan PowerPoint atau kode interop merujuk bentuk dengan handal dari mana saja dalam dokumen.<br/>            Baca-saja **int**.<br/>            Lihat juga [`Shape.unique_id`](/slides/python-net/id/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/id/aspose.slides/autoshape/alternative_text/) | Mengembalikan atau mengatur teks alternatif yang terkait dengan sebuah bentuk.<br/>            Baca/tulis **str**. |
| [`alternative_text_title`](/slides/python-net/id/aspose.slides/autoshape/alternative_text_title/) | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan sebuah bentuk.<br/>            Baca/tulis **str**. |
| [`name`](/slides/python-net/id/aspose.slides/autoshape/name/) | Mengembalikan atau mengatur nama sebuah bentuk.<br/>            Harus tidak None. Gunakan nilai string kosong jika diperlukan.<br/>            Baca/tulis **str**. |
| [`is_decorative`](/slides/python-net/id/aspose.slides/autoshape/is_decorative/) | Mendapatkan atau mengatur opsi 'Tandai sebagai dekoratif'<br/>            Baca/tulis **bool**. |
| [`shape_lock`](/slides/python-net/id/aspose.slides/autoshape/shape_lock/) | Mengembalikan kunci bentuk.<br/>            Baca-saja [`IAutoShapeLock`](/slides/python-net/id/aspose.slides/iautoshapelock). |
| [`is_grouped`](/slides/python-net/id/aspose.slides/autoshape/is_grouped/) | Menentukan apakah bentuk dikelompokkan.<br/>            Baca-saja **bool**. |
| [`parent_group`](/slides/python-net/id/aspose.slides/autoshape/parent_group/) | Mengembalikan objek GroupShape induk jika bentuk dikelompokkan. Jika tidak, mengembalikan None.<br/>            Baca-saja [`IGroupShape`](/slides/python-net/id/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/id/aspose.slides/autoshape/slide/) | Mengembalikan slide induk dari sebuah bentuk.<br/>            Baca-saja [`IBaseSlide`](/slides/python-net/id/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/id/aspose.slides/autoshape/presentation/) | Mengembalikan presentasi induk dari sebuah slide.<br/>            Baca-saja [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/id/aspose.slides/autoshape/shape_style/) | Mengembalikan objek gaya bentuk.<br/>            Baca-saja [`IShapeStyle`](/slides/python-net/id/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/id/aspose.slides/autoshape/shape_type/) | Mengembalikan atau mengatur tipe preset geometri.<br/>            Catatan: saat nilai berubah semua nilai penyesuaian akan direset ke nilai default.<br/>            Baca/tulis [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/id/aspose.slides/autoshape/adjustments/) | Mengembalikan koleksi nilai penyesuaian bentuk.<br/>            Baca-saja [`IAdjustValueCollection`](/slides/python-net/id/aspose.slides/iadjustvaluecollection). |
| [`auto_shape_lock`](/slides/python-net/id/aspose.slides/autoshape/auto_shape_lock/) | Mengembalikan kunci autoshape.<br/>            Baca-saja [`IAutoShapeLock`](/slides/python-net/id/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/id/aspose.slides/autoshape/text_frame/) | Mengembalikan objek TextFrame untuk AutoShape.<br/>            Baca-saja [`ITextFrame`](/slides/python-net/id/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/id/aspose.slides/autoshape/use_background_fill/) | Menentukan apakah autoshape ini harus diisi dengan latar belakang slide alih-alih ditentukan oleh style atau format isi.<br/>            Baca/tulis **bool**. |
| [`is_text_box`](/slides/python-net/id/aspose.slides/autoshape/is_text_box/) | Menentukan apakah bentuk adalah kotak teks. |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`get_image(self)`](/slides/python-net/id/aspose.slides/autoshape/get_image/#) | Mengembalikan thumbnail bentuk.<br/>            Tipe batas thumbnail bentuk ShapeThumbnailBounds.Shape digunakan secara default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/id/aspose.slides/autoshape/get_image/#shapethumbnailbounds-float-float) | Mengembalikan thumbnail bentuk. |
| [`write_as_svg(self, stream)`](/slides/python-net/id/aspose.slides/autoshape/write_as_svg/#iorawiobase) | Menyimpan konten Shape sebagai file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/id/aspose.slides/autoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Menyimpan konten Shape sebagai file SVG. |
| [`remove_placeholder(self)`](/slides/python-net/id/aspose.slides/autoshape/remove_placeholder/#) | Mendefinisikan bahwa bentuk ini bukan placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/id/aspose.slides/autoshape/add_placeholder/#iplaceholder) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [`get_base_placeholder(self)`](/slides/python-net/id/aspose.slides/autoshape/get_base_placeholder/#) | Mengembalikan shape placeholder dasar (shape dari tata letak dan/atau slide master yang diwarisi oleh shape saat ini).<br/>            None dikembalikan jika shape saat ini tidak diwarisi. |
| [`get_visual_bounds(self)`](/slides/python-net/id/aspose.slides/autoshape/get_visual_bounds/#) | Mendapatkan batas visual bentuk yang dihitung dari konten yang dirender. |
| [`get_geometry_paths(self)`](/slides/python-net/id/aspose.slides/autoshape/get_geometry_paths/#) | Mengembalikan salinan jalur shape geometri. Koordinat relatif terhadap sudut kiri atas shape. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/id/aspose.slides/autoshape/set_geometry_path/#igeometrypath) | Memperbarui geometri shape dari objek [`IGeometryPath`](/slides/python-net/id/aspose.slides/igeometrypath). Koordinat harus relatif terhadap sudut kiri<br/>             atas shape.<br/>             Mengubah tipe shape ([`GeometryShape.shape_type`](/slides/python-net/id/aspose.slides/geometryshape/shape_type)) menjadi [`ShapeType.CUSTOM`](/slides/python-net/id/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/id/aspose.slides/autoshape/set_geometry_paths/#listigeometrypath) | Memperbarui geometri shape dari array [`IGeometryPath`](/slides/python-net/id/aspose.slides/igeometrypath). Koordinat harus relatif terhadap sudut kiri<br/>             atas shape.<br/>             Mengubah tipe shape ([`GeometryShape.shape_type`](/slides/python-net/id/aspose.slides/geometryshape/shape_type)) menjadi [`ShapeType.CUSTOM`](/slides/python-net/id/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/id/aspose.slides/autoshape/create_shape_elements/#) | Membuat dan mengembalikan array elemen shape. |
| [`add_text_frame(self, text)`](/slides/python-net/id/aspose.slides/autoshape/add_text_frame/#str) | Menambahkan TextFrame baru ke sebuah shape.<br/>            Jika shape sudah memiliki TextFrame maka cukup mengubah teksnya. |

### Lihat Juga
* kelas [`AutoShape`](/slides/python-net/id/aspose.slides/autoshape)
* kelas [`GeometryShape`](/slides/python-net/id/aspose.slides/geometryshape)
* kelas [`Shape`](/slides/python-net/id/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)