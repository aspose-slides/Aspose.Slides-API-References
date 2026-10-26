---
title: Shape class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/shape/
---
## Shape kelas

Mewakili sebuah bentuk pada slide.

Tipe Shape menampilkan anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`is_text_holder`](/slides/python-net/id/aspose.slides/shape/is_text_holder/) | Menentukan apakah bentuk adalah TextHolder_PPT.<br/>            Hanya baca **bool**. |
| [`placeholder`](/slides/python-net/id/aspose.slides/shape/placeholder/) | Mengembalikan placeholder untuk sebuah bentuk. Mengembalikan None jika bentuk tidak memiliki placeholder.<br/>            Hanya baca [`IPlaceholder`](/slides/python-net/id/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/id/aspose.slides/shape/custom_data/) | Mengembalikan data kustom bentuk.<br/>            Hanya baca [`ICustomData`](/slides/python-net/id/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/id/aspose.slides/shape/raw_frame/) | Mengembalikan atau mengatur properti frame bentuk mentah.<br/>            Baca/tulis [`IShapeFrame`](/slides/python-net/id/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/id/aspose.slides/shape/frame/) | Mengembalikan atau mengatur properti frame bentuk.<br/>            Baca/tulis [`IShapeFrame`](/slides/python-net/id/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/id/aspose.slides/shape/line_format/) | Mengembalikan objek LineFormat yang berisi properti pemformatan garis untuk sebuah bentuk.<br/>            Catatan: dapat mengembalikan None untuk tipe bentuk tertentu yang tidak memiliki properti garis.<br/>            Hanya baca [`ILineFormat`](/slides/python-net/id/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/id/aspose.slides/shape/three_d_format/) | Mengembalikan objek ThreeDFormat yang berisi properti efek 3d untuk sebuah bentuk.<br/>            Catatan: dapat mengembalikan None untuk tipe bentuk tertentu yang tidak memiliki properti 3d.<br/>            Hanya baca [`IThreeDFormat`](/slides/python-net/id/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/id/aspose.slides/shape/effect_format/) | Mengembalikan objek EffectFormat yang berisi efek piksel yang diterapkan pada sebuah bentuk.<br/>            Catatan: dapat mengembalikan None untuk tipe bentuk tertentu yang tidak memiliki properti efek.<br/>            Hanya baca [`IEffectFormat`](/slides/python-net/id/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/id/aspose.slides/shape/fill_format/) | Mengembalikan objek FillFormat yang berisi properti pemformatan isi untuk sebuah bentuk.<br/>            Catatan: dapat mengembalikan None untuk tipe bentuk tertentu yang tidak memiliki properti isi.<br/>            Hanya baca [`IFillFormat`](/slides/python-net/id/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/id/aspose.slides/shape/hyperlink_click/) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse.<br/>            Baca/tulis [`IHyperlink`](/slides/python-net/id/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/id/aspose.slides/shape/hyperlink_mouse_over/) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk hover mouse.<br/>            Baca/tulis [`IHyperlink`](/slides/python-net/id/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/id/aspose.slides/shape/hyperlink_manager/) | Mengembalikan pengelola hyperlink.<br/>            Hanya baca [`IHyperlinkManager`](/slides/python-net/id/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/id/aspose.slides/shape/hidden/) | Menentukan apakah bentuk disembunyikan.<br/>            Baca/tulis **bool**. |
| [`z_order_position`](/slides/python-net/id/aspose.slides/shape/z_order_position/) | Mengembalikan posisi sebuah bentuk dalam urutan-z.<br/>            Shapes[0] mengembalikan bentuk di belakang urutan-z,<br/>            dan Shapes[Shapes.Count - 1] mengembalikan bentuk di depan urutan-z.<br/>            Hanya baca **int**. |
| [`connection_site_count`](/slides/python-net/id/aspose.slides/shape/connection_site_count/) | Mengembalikan jumlah situs sambungan pada bentuk.<br/>            Hanya baca **int**. |
| [`rotation`](/slides/python-net/id/aspose.slides/shape/rotation/) | Mengembalikan atau mengatur jumlah derajat bentuk yang diputar sekitar<br/>            sumbu-z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif<br/>            menunjukkan rotasi berlawanan arah jarum jam.<br/>            Baca/tulis **float**. |
| [`x`](/slides/python-net/id/aspose.slides/shape/x/) | Mendapatkan atau mengatur koordinat x sudut kiri atas bentuk, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`y`](/slides/python-net/id/aspose.slides/shape/y/) | Mendapatkan atau mengatur koordinat y sudut kiri atas bentuk, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`width`](/slides/python-net/id/aspose.slides/shape/width/) | Mendapatkan atau mengatur lebar bentuk, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`height`](/slides/python-net/id/aspose.slides/shape/height/) | Mendapatkan atau mengatur tinggi bentuk, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`black_white_mode`](/slides/python-net/id/aspose.slides/shape/black_white_mode/) | Properti menentukan bagaimana bentuk akan ditampilkan dalam mode tampilan hitam-putih..<br/>            Baca/tulis [`BlackWhiteMode`](/slides/python-net/id/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/id/aspose.slides/shape/unique_id/) | Mengembalikan pengidentifikasi internal berskala presentasi yang dimaksudkan untuk penggunaan oleh add-in atau kode lain.<br/>            Karena nilai ini dapat ditetapkan ulang oleh pengguna atau secara programatik, ia tidak boleh diperlakukan<br/>            sebagai kunci unik yang persisten.<br/>            Hanya baca **int**.<br/>            Lihat juga [`Shape.office_interop_shape_id`](/slides/python-net/id/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/id/aspose.slides/shape/office_interop_shape_id/) | Mengembalikan pengidentifikasi unik berskala slide yang tetap konstan selama masa hidup bentuk dan<br/>            memungkinkan PowerPoint atau kode interop merujuk bentuk dengan andal dari mana saja dalam dokumen.<br/>            Hanya baca **int**.<br/>            Lihat juga [`Shape.unique_id`](/slides/python-net/id/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/id/aspose.slides/shape/alternative_text/) | Mengembalikan atau mengatur teks alternatif yang terkait dengan bentuk.<br/>            Baca/tulis **str**. |
| [`alternative_text_title`](/slides/python-net/id/aspose.slides/shape/alternative_text_title/) | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan bentuk.<br/>            Baca/tulis **str**. |
| [`name`](/slides/python-net/id/aspose.slides/shape/name/) | Mengembalikan atau mengatur nama bentuk.<br/>            Harus tidak None. Gunakan nilai string kosong jika diperlukan.<br/>            Baca/tulis **str**. |
| [`is_decorative`](/slides/python-net/id/aspose.slides/shape/is_decorative/) | Mendapatkan atau mengatur opsi 'Mark as decorative'<br/>            Baca/tulis **bool**. |
| [`shape_lock`](/slides/python-net/id/aspose.slides/shape/shape_lock/) | Mengembalikan kunci bentuk.<br/>            Hanya baca [`IBaseShapeLock`](/slides/python-net/id/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/id/aspose.slides/shape/is_grouped/) | Menentukan apakah bentuk dikelompokkan.<br/>            Hanya baca **bool**. |
| [`parent_group`](/slides/python-net/id/aspose.slides/shape/parent_group/) | Mengembalikan objek GroupShape induk jika bentuk dikelompokkan. Jika tidak, mengembalikan None.<br/>            Hanya baca [`IGroupShape`](/slides/python-net/id/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/id/aspose.slides/shape/slide/) | Mengembalikan slide induk dari sebuah bentuk.<br/>            Hanya baca [`IBaseSlide`](/slides/python-net/id/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/id/aspose.slides/shape/presentation/) | Mengembalikan presentasi induk dari sebuah slide.<br/>            Hanya baca [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation). |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`get_image(self)`](/slides/python-net/id/aspose.slides/shape/get_image/#) | Mengembalikan thumbnail bentuk.<br/>            ShapeThumbnailBounds.Shape tipe batas thumbnail bentuk digunakan secara default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/id/aspose.slides/shape/get_image/#shapethumbnailbounds-float-float) | Mengembalikan thumbnail bentuk. |
| [`write_as_svg(self, stream)`](/slides/python-net/id/aspose.slides/shape/write_as_svg/#iorawiobase) | Menyimpan konten Shape sebagai file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/id/aspose.slides/shape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Menyimpan konten Shape sebagai file SVG. |
| [`remove_placeholder(self)`](/slides/python-net/id/aspose.slides/shape/remove_placeholder/#) | Mendefinisikan bahwa bentuk ini bukan placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/id/aspose.slides/shape/add_placeholder/#iplaceholder) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [`get_base_placeholder(self)`](/slides/python-net/id/aspose.slides/shape/get_base_placeholder/#) | Mengembalikan bentuk placeholder dasar (bentuk dari tata letak dan/atau slide master yang diwarisi oleh bentuk saat ini).<br/>            None dikembalikan jika bentuk saat ini tidak diwarisi. |
| [`get_visual_bounds(self)`](/slides/python-net/id/aspose.slides/shape/get_visual_bounds/#) | Mendapatkan batas visual bentuk yang dihitung dari kontennya yang dirender. |

### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)