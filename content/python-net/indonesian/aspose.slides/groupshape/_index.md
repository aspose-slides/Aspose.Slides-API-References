---
title: GroupShape class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/groupshape/
---
## GroupShape kelas

Mewakili sekelompok bentuk pada slide.

**Inheritance:**[`GroupShape`](/slides/python-net/id/aspose.slides/groupshape) → [`Shape`](/slides/python-net/id/aspose.slides/shape)

Tipe GroupShape mengekspos anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`is_text_holder`](/slides/python-net/id/aspose.slides/groupshape/is_text_holder/) | Menentukan apakah bentuk adalah TextHolder_PPT.<br/>            Hanya-baca **bool**. |
| [`placeholder`](/slides/python-net/id/aspose.slides/groupshape/placeholder/) | Mengembalikan placeholder untuk sebuah bentuk. Mengembalikan None jika bentuk tidak memiliki placeholder.<br/>            Hanya-baca [`IPlaceholder`](/slides/python-net/id/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/id/aspose.slides/groupshape/custom_data/) | Mengembalikan data khusus bentuk.<br/>            Hanya-baca [`ICustomData`](/slides/python-net/id/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/id/aspose.slides/groupshape/raw_frame/) | Mengembalikan atau mengatur properti frame bentuk mentah.<br/>            Baca/tulis [`IShapeFrame`](/slides/python-net/id/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/id/aspose.slides/groupshape/frame/) | Mengembalikan atau mengatur properti frame bentuk.<br/>            Baca/tulis [`IShapeFrame`](/slides/python-net/id/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/id/aspose.slides/groupshape/line_format/) | Mengembalikan objek LineFormat yang berisi properti pemformatan garis untuk sebuah bentuk.<br/>            Catatan: Mengembalikan None untuk objek GroupShape karena mereka tidak memiliki properti garis.<br/>            Hanya-baca [`ILineFormat`](/slides/python-net/id/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/id/aspose.slides/groupshape/three_d_format/) | Mengembalikan objek ThreeDFormat yang berisi properti efek 3d untuk sebuah bentuk.<br/>            Catatan: dapat mengembalikan None untuk tipe bentuk tertentu yang tidak memiliki properti 3d.<br/>            Hanya-baca [`IThreeDFormat`](/slides/python-net/id/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/id/aspose.slides/groupshape/effect_format/) | Mengembalikan objek EffectFormat yang berisi efek piksel yang diterapkan pada sebuah bentuk.<br/>            Catatan: dapat mengembalikan None untuk tipe bentuk tertentu yang tidak memiliki properti efek.<br/>            Hanya-baca [`IEffectFormat`](/slides/python-net/id/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/id/aspose.slides/groupshape/fill_format/) | Mengembalikan objek FillFormat yang berisi properti pemformatan isi untuk sebuah bentuk.<br/>            Catatan: dapat mengembalikan None untuk tipe bentuk tertentu yang tidak memiliki properti isi.<br/>            Hanya-baca [`IFillFormat`](/slides/python-net/id/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/id/aspose.slides/groupshape/hyperlink_click/) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse.<br/>            Baca/tulis [`IHyperlink`](/slides/python-net/id/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/id/aspose.slides/groupshape/hyperlink_mouse_over/) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk mouse over.<br/>            Baca/tulis [`IHyperlink`](/slides/python-net/id/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/id/aspose.slides/groupshape/hyperlink_manager/) | Mengembalikan manajer hyperlink.<br/>            Hanya-baca [`IHyperlinkManager`](/slides/python-net/id/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/id/aspose.slides/groupshape/hidden/) | Menentukan apakah bentuk disembunyikan.<br/>            Baca/tulis **bool**. |
| [`z_order_position`](/slides/python-net/id/aspose.slides/groupshape/z_order_position/) | Mengembalikan posisi sebuah bentuk dalam urutan z.<br/>            Shapes[0] mengembalikan bentuk di bagian belakang urutan z,<br/>            dan Shapes[Shapes.Count - 1] mengembalikan bentuk di bagian depan urutan z.<br/>            Hanya-baca **int**. |
| [`connection_site_count`](/slides/python-net/id/aspose.slides/groupshape/connection_site_count/) | Mengembalikan jumlah titik koneksi pada bentuk.<br/>            Hanya-baca **int**. |
| [`rotation`](/slides/python-net/id/aspose.slides/groupshape/rotation/) | Mengembalikan atau mengatur jumlah derajat bentuk yang ditentukan diputar mengelilingi<br/>            sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif<br/>            menunjukkan rotasi berlawanan arah jarum jam.<br/>            Baca/tulis **float**. |
| [`x`](/slides/python-net/id/aspose.slides/groupshape/x/) | Mengambil atau mengatur koordinat x sudut kiri atas bentuk, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`y`](/slides/python-net/id/aspose.slides/groupshape/y/) | Mengambil atau mengatur koordinat y sudut kiri atas bentuk, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`width`](/slides/python-net/id/aspose.slides/groupshape/width/) | Mengambil atau mengatur lebar bentuk, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`height`](/slides/python-net/id/aspose.slides/groupshape/height/) | Mengambil atau mengatur tinggi bentuk, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`black_white_mode`](/slides/python-net/id/aspose.slides/groupshape/black_white_mode/) | Properti menentukan bagaimana bentuk akan ditampilkan dalam mode tampilan hitam-putih..<br/>            Baca/tulis [`BlackWhiteMode`](/slides/python-net/id/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/id/aspose.slides/groupshape/unique_id/) | Mengembalikan pengenal internal berskala presentasi yang ditujukan untuk penggunaan oleh add-in atau kode lain.<br/>            Karena nilai ini dapat ditetapkan ulang oleh pengguna atau secara programatik, tidak boleh diperlakukan<br/>            sebagai kunci unik yang persisten.<br/>            Hanya-baca **int**.<br/>            Lihat juga [`Shape.office_interop_shape_id`](/slides/python-net/id/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/id/aspose.slides/groupshape/office_interop_shape_id/) | Mengembalikan pengenal unik berskala slide yang tetap konstan selama masa hidup bentuk dan<br/>            memungkinkan PowerPoint atau kode interop merujuk bentuk dengan andal dari mana saja dalam dokumen.<br/>            Hanya-baca **int**.<br/>            Lihat juga [`Shape.unique_id`](/slides/python-net/id/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/id/aspose.slides/groupshape/alternative_text/) | Mengembalikan atau mengatur teks alternatif yang terkait dengan bentuk.<br/>            Baca/tulis **str**. |
| [`alternative_text_title`](/slides/python-net/id/aspose.slides/groupshape/alternative_text_title/) | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan bentuk.<br/>            Baca/tulis **str**. |
| [`name`](/slides/python-net/id/aspose.slides/groupshape/name/) | Mengembalikan atau mengatur nama sebuah bentuk.<br/>            Harus tidak None. Gunakan nilai string kosong jika diperlukan.<br/>            Baca/tulis **str**. |
| [`is_decorative`](/slides/python-net/id/aspose.slides/groupshape/is_decorative/) | Mengambil atau mengatur opsi 'Mark as decorative'<br/>            Baca/tulis **bool**. |
| [`shape_lock`](/slides/python-net/id/aspose.slides/groupshape/shape_lock/) | Mengembalikan kunci bentuk.<br/>            Hanya-baca [`IGroupShapeLock`](/slides/python-net/id/aspose.slides/igroupshapelock). |
| [`is_grouped`](/slides/python-net/id/aspose.slides/groupshape/is_grouped/) | Menentukan apakah bentuk dikelompokkan.<br/>            Hanya-baca **bool**. |
| [`parent_group`](/slides/python-net/id/aspose.slides/groupshape/parent_group/) | Mengembalikan objek GroupShape induk jika bentuk dikelompokkan. Jika tidak mengembalikan None.<br/>            Hanya-baca [`IGroupShape`](/slides/python-net/id/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/id/aspose.slides/groupshape/slide/) | Mengembalikan slide induk dari sebuah bentuk.<br/>            Hanya-baca [`IBaseSlide`](/slides/python-net/id/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/id/aspose.slides/groupshape/presentation/) | Mengembalikan presentasi induk dari sebuah slide.<br/>            Hanya-baca [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation). |
| [`group_shape_lock`](/slides/python-net/id/aspose.slides/groupshape/group_shape_lock/) | Mengembalikan kunci bentuk.<br/>            Hanya-baca [`IGroupShapeLock`](/slides/python-net/id/aspose.slides/igroupshapelock). |
| [`shapes`](/slides/python-net/id/aspose.slides/groupshape/shapes/) | Mengembalikan koleksi bentuk di dalam grup.<br/>            Hanya-baca [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection). |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`get_image(self)`](/slides/python-net/id/aspose.slides/groupshape/get_image/#) | Mengembalikan thumbnail bentuk.<br/>            Tipe ShapeThumbnailBounds.Shape shape thumbnail bounds digunakan secara default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/id/aspose.slides/groupshape/get_image/#shapethumbnailbounds-float-float) | Mengembalikan thumbnail bentuk. |
| [`write_as_svg(self, stream)`](/slides/python-net/id/aspose.slides/groupshape/write_as_svg/#iorawiobase) | Menyimpan konten Shape sebagai file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/id/aspose.slides/groupshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Menyimpan konten Shape sebagai file SVG. |
| [`remove_placeholder(self)`](/slides/python-net/id/aspose.slides/groupshape/remove_placeholder/#) | Mendefinisikan bahwa bentuk ini bukan placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/id/aspose.slides/groupshape/add_placeholder/#iplaceholder) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [`get_base_placeholder(self)`](/slides/python-net/id/aspose.slides/groupshape/get_base_placeholder/#) | Mengembalikan bentuk placeholder dasar (bentuk dari layout dan/atau master slide yang diwarisi oleh bentuk saat ini).<br/>            None dikembalikan jika bentuk saat ini tidak diwarisi. |
| [`get_visual_bounds(self)`](/slides/python-net/id/aspose.slides/groupshape/get_visual_bounds/#) | Mengambil batas visual bentuk yang dihitung dari konten yang dirender. |

### Lihat Juga
* kelas [`GroupShape`](/slides/python-net/id/aspose.slides/groupshape)
* kelas [`Shape`](/slides/python-net/id/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)