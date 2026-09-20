---
title: Table class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/table/
---
## Table kelas

Represents a table on a slide.

**Inheritance:**[`Table`](/slides/python-net/id/aspose.slides/table) → [`GraphicalObject`](/slides/python-net/id/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/id/aspose.slides/shape)

The Table type exposes the following members:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`is_text_holder`](/slides/python-net/id/aspose.slides/table/is_text_holder/) | Menentukan apakah shape adalah TextHolder_PPT.<br/>            Baca-saja **bool**. |
| [`placeholder`](/slides/python-net/id/aspose.slides/table/placeholder/) | Mengembalikan placeholder untuk shape. Mengembalikan None jika shape tidak memiliki placeholder.<br/>            Baca-saja [`IPlaceholder`](/slides/python-net/id/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/id/aspose.slides/table/custom_data/) | Mengembalikan data khusus shape.<br/>            Baca-saja [`ICustomData`](/slides/python-net/id/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/id/aspose.slides/table/raw_frame/) | Mengembalikan atau mengatur properti frame shape mentah.<br/>            Baca/tulis [`IShapeFrame`](/slides/python-net/id/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/id/aspose.slides/table/frame/) | Mengembalikan atau mengatur properti frame shape.<br/>            Baca/tulis [`IShapeFrame`](/slides/python-net/id/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/id/aspose.slides/table/line_format/) | Mengembalikan objek LineFormat yang berisi properti pemformatan garis untuk shape.<br/>            Catatan: dapat mengembalikan None untuk tipe shape tertentu yang tidak memiliki properti garis.<br/>            Baca-saja [`ILineFormat`](/slides/python-net/id/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/id/aspose.slides/table/three_d_format/) | Mengembalikan objek ThreeDFormat yang berisi properti efek 3d untuk shape.<br/>            Catatan: dapat mengembalikan None untuk tipe shape tertentu yang tidak memiliki properti 3d.<br/>            Baca-saja [`IThreeDFormat`](/slides/python-net/id/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/id/aspose.slides/table/effect_format/) | Mengembalikan objek EffectFormat yang berisi efek piksel yang diterapkan pada shape.<br/>            Catatan: dapat mengembalikan None untuk tipe shape tertentu yang tidak memiliki properti efek.<br/>            Baca-saja [`IEffectFormat`](/slides/python-net/id/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/id/aspose.slides/table/fill_format/) | Mengembalikan objek TableFormat.FillFormat yang berisi pemformatan isi untuk Table.<br/>            Baca-saja [`IFillFormat`](/slides/python-net/id/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/id/aspose.slides/table/hyperlink_click/) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse.<br/>            Baca/tulis [`IHyperlink`](/slides/python-net/id/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/id/aspose.slides/table/hyperlink_mouse_over/) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk hover mouse.<br/>            Baca/tulis [`IHyperlink`](/slides/python-net/id/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/id/aspose.slides/table/hyperlink_manager/) | Mengembalikan manajer hyperlink.<br/>            Baca-saja [`IHyperlinkManager`](/slides/python-net/id/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/id/aspose.slides/table/hidden/) | Menentukan apakah shape disembunyikan.<br/>            Baca/tulis **bool**. |
| [`z_order_position`](/slides/python-net/id/aspose.slides/table/z_order_position/) | Mengembalikan posisi shape dalam urutan z.<br/>            Shapes[0] mengembalikan shape di belakang urutan z,<br/>            dan Shapes[Shapes.Count - 1] mengembalikan shape di depan urutan z.<br/>            Baca-saja **int**. |
| [`connection_site_count`](/slides/python-net/id/aspose.slides/table/connection_site_count/) | Mengembalikan jumlah situs koneksi pada shape.<br/>            Baca-saja **int**. |
| [`rotation`](/slides/python-net/id/aspose.slides/table/rotation/) | Mengembalikan atau mengatur jumlah derajat rotasi shape yang ditentukan sekitar sumbu z<br/>            nilai positif menunjukkan rotasi searah jarum jam; nilai negatif<br/>            menunjukkan rotasi berlawanan arah jarum jam.<br/>            Baca/tulis **float**. |
| [`x`](/slides/python-net/id/aspose.slides/table/x/) | Mengambil atau mengatur koordinat x sudut kiri atas shape, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`y`](/slides/python-net/id/aspose.slides/table/y/) | Mengambil atau mengatur koordinat y sudut kiri atas shape, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`width`](/slides/python-net/id/aspose.slides/table/width/) | Mengambil atau mengatur lebar shape, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`height`](/slides/python-net/id/aspose.slides/table/height/) | Mengambil atau mengatur tinggi shape, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`black_white_mode`](/slides/python-net/id/aspose.slides/table/black_white_mode/) | Properti menentukan bagaimana shape akan ditampilkan dalam mode hitam-putih..<br/>            Baca/tulis [`BlackWhiteMode`](/slides/python-net/id/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/id/aspose.slides/table/unique_id/) | Mengembalikan pengidentifikasi internal berskala presentasi yang dimaksudkan untuk digunakan oleh add-in atau kode lain.<br/>            Karena nilai ini dapat ditetapkan kembali oleh pengguna atau secara programatis, tidak boleh diperlakukan<br/>            sebagai kunci unik yang persistén.<br/>            Baca-saja **int**.<br/>            Lihat juga [`Shape.office_interop_shape_id`](/slides/python-net/id/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/id/aspose.slides/table/office_interop_shape_id/) | Mengembalikan pengidentifikasi unik berskala slide yang tetap konstan selama masa hidup shape dan<br/>            memungkinkan PowerPoint atau kode interop merujuk shape dengan andal dari mana saja dalam dokumen.<br/>            Baca-saja **int**.<br/>            Lihat juga [`Shape.unique_id`](/slides/python-net/id/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/id/aspose.slides/table/alternative_text/) | Mengembalikan atau mengatur teks alternatif yang terkait dengan shape.<br/>            Baca/tulis **str**. |
| [`alternative_text_title`](/slides/python-net/id/aspose.slides/table/alternative_text_title/) | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan shape.<br/>            Baca/tulis **str**. |
| [`name`](/slides/python-net/id/aspose.slides/table/name/) | Mengembalikan atau mengatur nama shape.<br/>            Harus tidak None. Gunakan nilai string kosong bila diperlukan.<br/>            Baca/tulis **str**. |
| [`is_decorative`](/slides/python-net/id/aspose.slides/table/is_decorative/) | Mengambil atau mengatur opsi 'Mark as decorative'<br/>            Baca/tulis **bool**. |
| [`shape_lock`](/slides/python-net/id/aspose.slides/table/shape_lock/) | Mengembalikan kunci shape.<br/>            Baca-saja [`IGraphicalObjectLock`](/slides/python-net/id/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/id/aspose.slides/table/is_grouped/) | Menentukan apakah shape dikelompokkan.<br/>            Baca-saja **bool**. |
| [`parent_group`](/slides/python-net/id/aspose.slides/table/parent_group/) | Mengembalikan objek GroupShape induk jika shape dikelompokkan. Jika tidak, mengembalikan None.<br/>            Baca-saja [`IGroupShape`](/slides/python-net/id/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/id/aspose.slides/table/slide/) | Mengembalikan slide induk dari shape.<br/>            Baca-saja [`IBaseSlide`](/slides/python-net/id/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/id/aspose.slides/table/presentation/) | Mengembalikan presentasi induk dari slide.<br/>            Baca-saja [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/id/aspose.slides/table/graphical_object_lock/) | Mengembalikan kunci shape.<br/>            Baca-saja [`IGraphicalObjectLock`](/slides/python-net/id/aspose.slides/igraphicalobjectlock). |
| [`rows`](/slides/python-net/id/aspose.slides/table/rows/) | Mengembalikan koleksi baris.<br/>            Baca-saja [`IRowCollection`](/slides/python-net/id/aspose.slides/irowcollection). |
| [`columns`](/slides/python-net/id/aspose.slides/table/columns/) | Mengembalikan koleksi kolom.<br/>            Baca-saja [`IColumnCollection`](/slides/python-net/id/aspose.slides/icolumncollection). |
| [`table_format`](/slides/python-net/id/aspose.slides/table/table_format/) | Mengembalikan objek TableFormat yang berisi properti pemformatan untuk tabel ini.<br/>            Baca-saja [`ITableFormat`](/slides/python-net/id/aspose.slides/itableformat). |
| [`style_preset`](/slides/python-net/id/aspose.slides/table/style_preset/) | Mengambil atau mengatur gaya tabel bawaan.<br/>            Baca/tulis [`TableStylePreset`](/slides/python-net/id/aspose.slides/tablestylepreset). |
| [`right_to_left`](/slides/python-net/id/aspose.slides/table/right_to_left/) | Menentukan apakah tabel memiliki urutan bacaan kanan ke kiri.<br/>            Baca-tulis **bool**. |
| [`first_row`](/slides/python-net/id/aspose.slides/table/first_row/) | Menentukan apakah baris pertama tabel harus digambar dengan pemformatan khusus.<br/>            Baca/tulis **bool**. |
| [`first_col`](/slides/python-net/id/aspose.slides/table/first_col/) | Menentukan apakah kolom pertama tabel harus digambar dengan pemformatan khusus.<br/>            Baca/tulis **bool**. |
| [`last_row`](/slides/python-net/id/aspose.slides/table/last_row/) | Menentukan apakah baris terakhir tabel harus digambar dengan pemformatan khusus.<br/>            Baca/tulis **bool**. |
| [`last_col`](/slides/python-net/id/aspose.slides/table/last_col/) | Menentukan apakah kolom terakhir tabel harus digambar dengan pemformatan khusus.<br/>            Baca/tulis **bool**. |
| [`horizontal_banding`](/slides/python-net/id/aspose.slides/table/horizontal_banding/) | Menentukan apakah baris genap harus digambar dengan pemformatan berbeda.<br/>            Baca/tulis **bool**. |
| [`vertical_banding`](/slides/python-net/id/aspose.slides/table/vertical_banding/) | Menentukan apakah kolom genap harus digambar dengan pemformatan berbeda.<br/>            Baca/tulis **bool**. |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`get_image(self)`](/slides/python-net/id/aspose.slides/table/get_image/#) | Mengembalikan thumbnail shape.<br/>            Tipe ShapeThumbnailBounds.Shape untuk batas thumbnail shape digunakan secara default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/id/aspose.slides/table/get_image/#shapethumbnailbounds-float-float) | Mengembalikan thumbnail shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/id/aspose.slides/table/write_as_svg/#iorawiobase) | Menyimpan konten Shape sebagai file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/id/aspose.slides/table/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Menyimpan konten Shape sebagai file SVG. |
| [`set_text_format(self, source)`](/slides/python-net/id/aspose.slides/table/set_text_format/#iportionformat) | Menetapkan properti format bagian yang ditentukan ke semua bagian sel tabel. |
| [`set_text_format(self, source)`](/slides/python-net/id/aspose.slides/table/set_text_format/#iparagraphformat) | Menetapkan properti format paragraf yang ditentukan ke semua paragraf sel tabel. |
| [`set_text_format(self, source)`](/slides/python-net/id/aspose.slides/table/set_text_format/#itextframeformat) | Menetapkan properti format bingkai teks yang ditentukan ke semua bingkai teks sel tabel. |
| [`remove_placeholder(self)`](/slides/python-net/id/aspose.slides/table/remove_placeholder/#) | Mendefinisikan bahwa shape ini bukan placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/id/aspose.slides/table/add_placeholder/#iplaceholder) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [`get_base_placeholder(self)`](/slides/python-net/id/aspose.slides/table/get_base_placeholder/#) | Mengembalikan shape placeholder dasar (shape dari tata letak dan/atau master slide yang diwarisi oleh shape saat ini).<br/>            None dikembalikan jika shape saat ini tidak diwarisi. |
| [`get_visual_bounds(self)`](/slides/python-net/id/aspose.slides/table/get_visual_bounds/#) | Mengambil batas visual shape yang dihitung dari konten yang dirender. |
| [`merge_cells(self, cell1, cell2, allow_splitting)`](/slides/python-net/id/aspose.slides/table/merge_cells/#icell-icell-bool) | Menggabungkan sel tetangga. |

### Lihat Juga
* kelas [`GraphicalObject`](/slides/python-net/id/aspose.slides/graphicalobject)
* kelas [`Shape`](/slides/python-net/id/aspose.slides/shape)
* kelas [`Table`](/slides/python-net/id/aspose.slides/table)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)