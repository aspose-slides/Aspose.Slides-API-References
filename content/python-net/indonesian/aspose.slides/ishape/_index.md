---
title: IShape class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ishape/
---
## IShape kelas

Mewakili sebuah shape pada slide.

Tipe IShape menampilkan anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`is_text_holder`](/slides/python-net/id/aspose.slides/ishape/is_text_holder/) | Menentukan apakah shape adalah TextHolder.<br/>            Hanya-baca **bool**. |
| [`placeholder`](/slides/python-net/id/aspose.slides/ishape/placeholder/) | Mengembalikan placeholder untuk sebuah shape.<br/>            Hanya-baca [`IPlaceholder`](/slides/python-net/id/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/id/aspose.slides/ishape/custom_data/) | Mengembalikan data khusus shape.<br/>            Hanya-baca [`ICustomData`](/slides/python-net/id/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/id/aspose.slides/ishape/raw_frame/) | Mengembalikan atau mengatur properti kerangka shape mentah.<br/>            Baca/tulis [`IShapeFrame`](/slides/python-net/id/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/id/aspose.slides/ishape/frame/) | Mengembalikan atau mengatur properti kerangka shape.<br/>            Baca/tulis [`IShapeFrame`](/slides/python-net/id/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/id/aspose.slides/ishape/line_format/) | Mengembalikan objek LineFormat yang berisi properti pemformatan garis untuk sebuah shape.<br/>            Hanya-baca [`ILineFormat`](/slides/python-net/id/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/id/aspose.slides/ishape/three_d_format/) | Mengembalikan objek ThreeDFormat yang berisi properti pemformatan tiga dimensi untuk sebuah shape.<br/>            Hanya-baca [`IThreeDFormat`](/slides/python-net/id/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/id/aspose.slides/ishape/effect_format/) | Mengembalikan objek EffectFormat yang berisi efek piksel yang diterapkan pada sebuah shape.<br/>            Hanya-baca [`IEffectFormat`](/slides/python-net/id/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/id/aspose.slides/ishape/fill_format/) | Mengembalikan objek FillFormat yang berisi properti pemformatan isi untuk sebuah shape.<br/>            Hanya-baca [`IFillFormat`](/slides/python-net/id/aspose.slides/ifillformat). |
| [`hidden`](/slides/python-net/id/aspose.slides/ishape/hidden/) | Menentukan apakah shape disembunyikan.<br/>            Baca/tulis **bool**. |
| [`z_order_position`](/slides/python-net/id/aspose.slides/ishape/z_order_position/) | Mengembalikan posisi shape dalam urutan z.<br/>            Shapes[0] mengembalikan shape di paling belakang urutan z,<br/>            dan Shapes[Shapes.Count - 1] mengembalikan shape di paling depan urutan z.<br/>            Hanya-baca **int**. |
| [`connection_site_count`](/slides/python-net/id/aspose.slides/ishape/connection_site_count/) | Mengembalikan jumlah titik koneksi pada shape.<br/>            Hanya-baca **int**. |
| [`rotation`](/slides/python-net/id/aspose.slides/ishape/rotation/) | Mengembalikan atau mengatur jumlah derajat shape yang diputar sekitar<br/>            sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif<br/>            menunjukkan rotasi berlawanan arah jarum jam.<br/>            Baca/tulis **float**. |
| [`x`](/slides/python-net/id/aspose.slides/ishape/x/) | Mendapatkan atau mengatur koordinat x sudut kiri atas shape, diukur dalam point.<br/>            Baca/tulis **float**. |
| [`y`](/slides/python-net/id/aspose.slides/ishape/y/) | Mendapatkan atau mengatur koordinat y sudut kiri atas shape, diukur dalam point.<br/>            Baca/tulis **float**. |
| [`width`](/slides/python-net/id/aspose.slides/ishape/width/) | Mendapatkan atau mengatur lebar shape, diukur dalam point.<br/>            Baca/tulis **float**. |
| [`height`](/slides/python-net/id/aspose.slides/ishape/height/) | Mendapatkan atau mengatur tinggi shape, diukur dalam point.<br/>            Baca/tulis **float**. |
| [`alternative_text`](/slides/python-net/id/aspose.slides/ishape/alternative_text/) | Mengembalikan atau mengatur teks alternatif yang terkait dengan sebuah shape.<br/>            Baca/tulis **str**. |
| [`alternative_text_title`](/slides/python-net/id/aspose.slides/ishape/alternative_text_title/) | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan sebuah shape.<br/>            Baca/tulis **str**. |
| [`name`](/slides/python-net/id/aspose.slides/ishape/name/) | Mengembalikan atau mengatur nama sebuah shape.<br/>            Baca/tulis **str**. |
| [`is_decorative`](/slides/python-net/id/aspose.slides/ishape/is_decorative/) | Mendapatkan atau mengatur opsi 'Mark as decorative'<br/>            Baca/tulis **bool**. |
| [`shape_lock`](/slides/python-net/id/aspose.slides/ishape/shape_lock/) | Mengembalikan kunci shape.<br/>            Hanya-baca [`IBaseShapeLock`](/slides/python-net/id/aspose.slides/ibaseshapelock). |
| [`unique_id`](/slides/python-net/id/aspose.slides/ishape/unique_id/) | Mengembalikan pengenal internal yang berskala presentasi yang dimaksudkan untuk digunakan oleh add-in atau kode lainnya.<br/>            Karena nilai ini dapat ditetapkan ulang oleh pengguna atau secara programatik, tidak boleh diperlakukan<br/>            sebagai kunci unik yang persisten.<br/>            Hanya-baca **int**.<br/>            Lihat juga [`IShape.office_interop_shape_id`](/slides/python-net/id/aspose.slides/ishape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/id/aspose.slides/ishape/office_interop_shape_id/) | Mengembalikan pengenal unik berskala slide yang tetap konstan selama masa hidup shape dan<br/>            memungkinkan PowerPoint atau kode interop secara andal merujuk shape dari mana saja dalam dokumen.<br/>            Hanya-baca **int**.<br/>            Lihat juga [`IShape.unique_id`](/slides/python-net/id/aspose.slides/ishape/unique_id). |
| [`is_grouped`](/slides/python-net/id/aspose.slides/ishape/is_grouped/) | Menentukan apakah shape dikelompokkan.<br/>            Hanya-baca **bool**. |
| [`black_white_mode`](/slides/python-net/id/aspose.slides/ishape/black_white_mode/) | Properti menentukan bagaimana shape akan dirender dalam mode tampilan hitam-putih..<br/>            Baca/tulis [`BlackWhiteMode`](/slides/python-net/id/aspose.slides/blackwhitemode). |
| [`parent_group`](/slides/python-net/id/aspose.slides/ishape/parent_group/) | Mengembalikan objek GroupShape induk jika shape dikelompokkan. Jika tidak, mengembalikan None.<br/>            Hanya-baca [`IGroupShape`](/slides/python-net/id/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/id/aspose.slides/ishape/slide/) |  |
| [`presentation`](/slides/python-net/id/aspose.slides/ishape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/id/aspose.slides/ishape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/id/aspose.slides/ishape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/id/aspose.slides/ishape/hyperlink_manager/) |  |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`get_image(self)`](/slides/python-net/id/aspose.slides/ishape/get_image/#) | Mengembalikan thumbnail shape.<br/>            Tipe batas thumbnail ShapeThumbnailBounds.Shape digunakan secara default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/id/aspose.slides/ishape/get_image/#shapethumbnailbounds-float-float) | Mengembalikan thumbnail shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/id/aspose.slides/ishape/write_as_svg/#iorawiobase) | Menyimpan konten Shape sebagai file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/id/aspose.slides/ishape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Menyimpan konten Shape sebagai file SVG. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/id/aspose.slides/ishape/add_placeholder/#iplaceholder) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [`remove_placeholder(self)`](/slides/python-net/id/aspose.slides/ishape/remove_placeholder/#) | Mendefinisikan bahwa shape ini bukan placeholder. |
| [`get_base_placeholder(self)`](/slides/python-net/id/aspose.slides/ishape/get_base_placeholder/#) | Mengembalikan shape placeholder dasar (shape dari tata letak dan/atau master slide yang mewarisi shape saat ini).<br/>            None dikembalikan jika shape saat ini tidak diwarisi. |

### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)