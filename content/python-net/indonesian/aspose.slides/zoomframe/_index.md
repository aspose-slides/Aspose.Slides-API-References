---
title: ZoomFrame class
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides/zoomframe/
---
## ZoomFrame kelas

Represents a Slide Zoom object in a slide.

**Inheritance:**[`ZoomFrame`](/slides/python-net/id/aspose.slides/zoomframe) → [`ZoomObject`](/slides/python-net/id/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/id/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/id/aspose.slides/shape)

The ZoomFrame type exposes the following members:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`is_text_holder`](/slides/python-net/id/aspose.slides/zoomframe/is_text_holder/) | Menentukan apakah shape adalah TextHolder_PPT.<br/>            Baca-saja **bool**. |
| [`placeholder`](/slides/python-net/id/aspose.slides/zoomframe/placeholder/) | Mengembalikan placeholder untuk sebuah shape. Mengembalikan None jika shape tidak memiliki placeholder.<br/>            Baca-saja [`IPlaceholder`](/slides/python-net/id/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/id/aspose.slides/zoomframe/custom_data/) | Mengembalikan data khusus shape.<br/>            Baca-saja [`ICustomData`](/slides/python-net/id/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/id/aspose.slides/zoomframe/raw_frame/) | Mengembalikan atau mengatur properti frame shape mentah.<br/>            Baca/tulis [`IShapeFrame`](/slides/python-net/id/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/id/aspose.slides/zoomframe/frame/) | Mengembalikan atau mengatur properti frame shape.<br/>            Baca/tulis [`IShapeFrame`](/slides/python-net/id/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/id/aspose.slides/zoomframe/line_format/) | Mengembalikan objek LineFormat yang berisi properti pemformatan garis untuk sebuah shape.<br/>            Catatan: dapat mengembalikan None untuk tipe shape tertentu yang tidak memiliki properti garis.<br/>            Baca-saja [`ILineFormat`](/slides/python-net/id/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/id/aspose.slides/zoomframe/three_d_format/) | Mengembalikan objek ThreeDFormat yang berisi properti efek 3d untuk sebuah shape.<br/>            Catatan: dapat mengembalikan None untuk tipe shape tertentu yang tidak memiliki properti 3d.<br/>            Baca-saja [`IThreeDFormat`](/slides/python-net/id/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/id/aspose.slides/zoomframe/effect_format/) | Mengembalikan objek EffectFormat yang berisi efek piksel yang diterapkan pada sebuah shape.<br/>            Catatan: dapat mengembalikan None untuk tipe shape tertentu yang tidak memiliki properti efek.<br/>            Baca-saja [`IEffectFormat`](/slides/python-net/id/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/id/aspose.slides/zoomframe/fill_format/) | Mengembalikan objek FillFormat yang berisi properti pemformatan isi untuk sebuah shape.<br/>            Catatan: dapat mengembalikan None untuk tipe shape tertentu yang tidak memiliki properti isi.<br/>            Baca-saja [`IFillFormat`](/slides/python-net/id/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/id/aspose.slides/zoomframe/hyperlink_click/) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse.<br/>            Baca/tulis [`IHyperlink`](/slides/python-net/id/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/id/aspose.slides/zoomframe/hyperlink_mouse_over/) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk mouse over.<br/>            Baca/tulis [`IHyperlink`](/slides/python-net/id/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/id/aspose.slides/zoomframe/hyperlink_manager/) | Mengembalikan pengelola hyperlink.<br/>            Baca-saja [`IHyperlinkManager`](/slides/python-net/id/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/id/aspose.slides/zoomframe/hidden/) | Menentukan apakah shape tersembunyi.<br/>            Baca/tulis **bool**. |
| [`z_order_position`](/slides/python-net/id/aspose.slides/zoomframe/z_order_position/) | Mengembalikan posisi sebuah shape dalam urutan z.<br/>            Shapes[0] mengembalikan shape di belakang urutan z,<br/>            dan Shapes[Shapes.Count - 1] mengembalikan shape di depan urutan z.<br/>            Baca-saja **int**. |
| [`connection_site_count`](/slides/python-net/id/aspose.slides/zoomframe/connection_site_count/) | Mengembalikan jumlah titik koneksi pada shape.<br/>            Baca-saja **int**. |
| [`rotation`](/slides/python-net/id/aspose.slides/zoomframe/rotation/) | Mengembalikan atau mengatur jumlah derajat rotasi shape yang ditentukan di sekitar sumbu z.<br/>            Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif<br/>            menunjukkan rotasi berlawanan arah jarum jam.<br/>            Baca/tulis **float**. |
| [`x`](/slides/python-net/id/aspose.slides/zoomframe/x/) | Mengambil atau mengatur koordinat x sudut kiri-atas shape, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`y`](/slides/python-net/id/aspose.slides/zoomframe/y/) | Mengambil atau mengatur koordinat y sudut kiri-atas shape, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`width`](/slides/python-net/id/aspose.slides/zoomframe/width/) | Mengambil atau mengatur lebar shape, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`height`](/slides/python-net/id/aspose.slides/zoomframe/height/) | Mengambil atau mengatur tinggi shape, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`black_white_mode`](/slides/python-net/id/aspose.slides/zoomframe/black_white_mode/) | Properti menentukan bagaimana shape akan ditampilkan dalam mode tampilan hitam-putih..<br/>            Baca/tulis [`BlackWhiteMode`](/slides/python-net/id/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/id/aspose.slides/zoomframe/unique_id/) | Mengembalikan pengidentifikasi internal dengan cakupan presentasi yang dimaksudkan untuk digunakan oleh add-in atau kode lain.<br/>            Karena nilai ini dapat dipilih ulang oleh pengguna atau secara programatik, ia tidak boleh diperlakukan<br/>            sebagai kunci unik yang persisten.<br/>            Baca-saja **int**.<br/>            Lihat juga [`Shape.office_interop_shape_id`](/slides/python-net/id/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/id/aspose.slides/zoomframe/office_interop_shape_id/) | Mengembalikan pengidentifikasi unik dengan cakupan slide yang tetap konstan selama masa hidup shape dan<br/>            memungkinkan PowerPoint atau kode interop merujuk shape secara andal dari mana saja dalam dokumen.<br/>            Baca-saja **int**.<br/>            Lihat juga [`Shape.unique_id`](/slides/python-net/id/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/id/aspose.slides/zoomframe/alternative_text/) | Mengembalikan atau mengatur teks alternatif yang terkait dengan sebuah shape.<br/>            Baca/tulis **str**. |
| [`alternative_text_title`](/slides/python-net/id/aspose.slides/zoomframe/alternative_text_title/) | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan sebuah shape.<br/>            Baca/tulis **str**. |
| [`name`](/slides/python-net/id/aspose.slides/zoomframe/name/) | Mengembalikan atau mengatur nama sebuah shape.<br/>            Tidak boleh None. Gunakan nilai string kosong jika diperlukan.<br/>            Baca/tulis **str**. |
| [`is_decorative`](/slides/python-net/id/aspose.slides/zoomframe/is_decorative/) | Mendapatkan atau mengatur opsi 'Mark as decorative'<br/>            Baca/tulis **bool**. |
| [`shape_lock`](/slides/python-net/id/aspose.slides/zoomframe/shape_lock/) | Mengembalikan kunci (locks) shape.<br/>            Baca-saja [`IGraphicalObjectLock`](/slides/python-net/id/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/id/aspose.slides/zoomframe/is_grouped/) | Menentukan apakah shape dikelompokkan.<br/>            Baca-saja **bool**. |
| [`parent_group`](/slides/python-net/id/aspose.slides/zoomframe/parent_group/) | Mengembalikan objek GroupShape induk jika shape dikelompokkan. Jika tidak, mengembalikan None.<br/>            Baca-saja [`IGroupShape`](/slides/python-net/id/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/id/aspose.slides/zoomframe/slide/) | Mengembalikan slide induk dari sebuah shape.<br/>            Baca-saja [`IBaseSlide`](/slides/python-net/id/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/id/aspose.slides/zoomframe/presentation/) | Mengembalikan presentasi induk dari sebuah slide.<br/>            Baca-saja [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/id/aspose.slides/zoomframe/graphical_object_lock/) | Mengembalikan kunci (locks) shape.<br/>            Baca-saja [`IGraphicalObjectLock`](/slides/python-net/id/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/id/aspose.slides/zoomframe/image_type/) | Mendapatkan atau mengatur tipe gambar dari objek zoom.<br/>            Baca/tulis [`ZoomImageType`](/slides/python-net/id/aspose.slides/zoomimagetype).<br/>            Nilai default: Preview |
| [`return_to_parent`](/slides/python-net/id/aspose.slides/zoomframe/return_to_parent/) | Mendapatkan atau mengatur perilaku navigasi dalam slideshow.<br/>            Baca/tulis **bool**.<br/>            Nilai default: false |
| [`show_background`](/slides/python-net/id/aspose.slides/zoomframe/show_background/) | Mendapatkan atau mengatur nilai yang menentukan apakah Zoom akan menggunakan latar belakang slide tujuan.<br/>            Baca/tulis **bool**.<br/>            Nilai default: true |
| [`zoom_image`](/slides/python-net/id/aspose.slides/zoomframe/zoom_image/) | Mendapatkan atau mengatur gambar untuk objek zoom.<br/>            Baca/tulis [`IPPImage`](/slides/python-net/id/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/id/aspose.slides/zoomframe/transition_duration/) | Mendapatkan atau mengatur durasi transisi antara Zoom dan slide.<br/>            Baca/tulis **float**.<br/>            Nilai default: 1.0f |
| [`target_slide`](/slides/python-net/id/aspose.slides/zoomframe/target_slide/) | Mendapatkan atau mengatur objek slide yang ditautkan oleh objek Slide Zoom.<br/>            Baca/tulis [`ISlide`](/slides/python-net/id/aspose.slides/islide). |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`get_image(self)`](/slides/python-net/id/aspose.slides/zoomframe/get_image/#) | Mengembalikan thumbnail shape.<br/>            Tipe ShapeThumbnailBounds.Shape digunakan secara default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/id/aspose.slides/zoomframe/get_image/#shapethumbnailbounds-float-float) | Mengembalikan thumbnail shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/id/aspose.slides/zoomframe/write_as_svg/#iorawiobase) | Menyimpan konten Shape sebagai file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/id/aspose.slides/zoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Menyimpan konten Shape sebagai file SVG. |
| [`remove_placeholder(self)`](/slides/python-net/id/aspose.slides/zoomframe/remove_placeholder/#) | Mendefinisikan bahwa shape ini bukan placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/id/aspose.slides/zoomframe/add_placeholder/#iplaceholder) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [`get_base_placeholder(self)`](/slides/python-net/id/aspose.slides/zoomframe/get_base_placeholder/#) | Mengembalikan shape placeholder dasar (shape dari tata letak dan/atau slide master yang diwarisi oleh shape saat ini).<br/>            None dikembalikan jika shape saat ini tidak diwarisi. |
| [`get_visual_bounds(self)`](/slides/python-net/id/aspose.slides/zoomframe/get_visual_bounds/#) | Mendapatkan batas visual shape yang dihitung dari kontennya yang dirender. |

### Lihat Juga
* kelas [`GraphicalObject`](/slides/python-net/id/aspose.slides/graphicalobject)
* kelas [`Shape`](/slides/python-net/id/aspose.slides/shape)
* kelas [`ZoomFrame`](/slides/python-net/id/aspose.slides/zoomframe)
* kelas [`ZoomObject`](/slides/python-net/id/aspose.slides/zoomobject)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)