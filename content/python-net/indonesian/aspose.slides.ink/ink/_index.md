---
title: Ink class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.ink/ink/
---
## Kelas Ink

Represents an ink object on a slide.

**Pewarisan:**[`Ink`](/slides/python-net/id/aspose.slides.ink/ink) → [`GraphicalObject`](/slides/python-net/id/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/id/aspose.slides/shape)

The Ink type exposes the following members:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`is_text_holder`](/slides/python-net/id/aspose.slides.ink/ink/is_text_holder/) | Menentukan apakah shape adalah TextHolder_PPT.<br/>            **Baca-saja** **bool**. |
| [`placeholder`](/slides/python-net/id/aspose.slides.ink/ink/placeholder/) | Mengembalikan placeholder untuk shape. Mengembalikan None jika shape tidak memiliki placeholder.<br/>            **Baca-saja** [`IPlaceholder`](/slides/python-net/id/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/id/aspose.slides.ink/ink/custom_data/) | Mengembalikan data kustom shape.<br/>            **Baca-saja** [`ICustomData`](/slides/python-net/id/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/id/aspose.slides.ink/ink/raw_frame/) | Mengembalikan atau mengatur properti frame shape mentah.<br/>            **Baca/tulis** [`IShapeFrame`](/slides/python-net/id/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/id/aspose.slides.ink/ink/frame/) | Mengembalikan atau mengatur properti frame shape.<br/>            **Baca/tulis** [`IShapeFrame`](/slides/python-net/id/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/id/aspose.slides.ink/ink/line_format/) | Menampilkan objek LineFormat yang berisi properti pemformatan garis untuk shape.<br/>            Catatan: dapat mengembalikan None untuk beberapa tipe shape yang tidak memiliki properti garis.<br/>            **Baca-saja** [`ILineFormat`](/slides/python-net/id/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/id/aspose.slides.ink/ink/three_d_format/) | Menampilkan objek ThreeDFormat yang berisi properti efek 3D untuk shape.<br/>            Catatan: dapat mengembalikan None untuk beberapa tipe shape yang tidak memiliki properti 3D.<br/>            **Baca-saja** [`IThreeDFormat`](/slides/python-net/id/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/id/aspose.slides.ink/ink/effect_format/) | Menampilkan objek EffectFormat yang berisi efek piksel yang diterapkan pada shape.<br/>            Catatan: dapat mengembalikan None untuk beberapa tipe shape yang tidak memiliki properti efek.<br/>            **Baca-saja** [`IEffectFormat`](/slides/python-net/id/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/id/aspose.slides.ink/ink/fill_format/) | Menampilkan objek FillFormat yang berisi properti pemformatan isian untuk shape.<br/>            Catatan: dapat mengembalikan None untuk beberapa tipe shape yang tidak memiliki properti isian.<br/>            **Baca-saja** [`IFillFormat`](/slides/python-net/id/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/id/aspose.slides.ink/ink/hyperlink_click/) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse.<br/>            **Baca/tulis** [`IHyperlink`](/slides/python-net/id/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/id/aspose.slides.ink/ink/hyperlink_mouse_over/) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk hover mouse.<br/>            **Baca/tulis** [`IHyperlink`](/slides/python-net/id/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/id/aspose.slides.ink/ink/hyperlink_manager/) | Mengembalikan manajer hyperlink.<br/>            **Baca-saja** [`IHyperlinkManager`](/slides/python-net/id/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/id/aspose.slides.ink/ink/hidden/) | Menentukan apakah shape disembunyikan.<br/>            **Baca/tulis** **bool**. |
| [`z_order_position`](/slides/python-net/id/aspose.slides.ink/ink/z_order_position/) | Mengembalikan posisi shape dalam urutan z.<br/>            Shapes[0] mengembalikan shape di bagian belakang urutan z,<br/>            dan Shapes[Shapes.Count - 1] mengembalikan shape di bagian depan urutan z.<br/>            **Baca-saja** **int**. |
| [`connection_site_count`](/slides/python-net/id/aspose.slides.ink/ink/connection_site_count/) | Mengembalikan jumlah situs koneksi pada shape.<br/>            **Baca-saja** **int**. |
| [`rotation`](/slides/python-net/id/aspose.slides.ink/ink/rotation/) | Mengembalikan atau mengatur jumlah derajat rotasi shape tertentu di sekitar<br/>            sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif<br/>            menunjukkan rotasi berlawanan arah jarum jam.<br/>            **Baca/tulis** **float**. |
| [`x`](/slides/python-net/id/aspose.slides.ink/ink/x/) | Mengambil atau mengatur koordinat x sudut kiri atas shape, diukur dalam poin.<br/>            **Baca/tulis** **float**. |
| [`y`](/slides/python-net/id/aspose.slides.ink/ink/y/) | Mengambil atau mengatur koordinat y sudut kiri atas shape, diukur dalam poin.<br/>            **Baca/tulis** **float**. |
| [`width`](/slides/python-net/id/aspose.slides.ink/ink/width/) | Mengambil atau mengatur lebar shape, diukur dalam poin.<br/>            **Baca/tulis** **float**. |
| [`height`](/slides/python-net/id/aspose.slides.ink/ink/height/) | Mengambil atau mengatur tinggi shape, diukur dalam poin.<br/>            **Baca/tulis** **float**. |
| [`black_white_mode`](/slides/python-net/id/aspose.slides.ink/ink/black_white_mode/) | Properti yang menentukan bagaimana shape akan dirender dalam mode tampilan hitam-putih.<br/>            **Baca/tulis** [`BlackWhiteMode`](/slides/python-net/id/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/id/aspose.slides.ink/ink/unique_id/) | Mengembalikan pengenal internal berskala presentasi yang dimaksudkan untuk digunakan oleh add-in atau kode lain.<br/>            Karena nilai ini dapat dipilih ulang oleh pengguna atau secara programatis, tidak boleh diperlakukan<br/>            sebagai kunci unik yang persisten.<br/>            **Baca-saja** **int**.<br/>            Lihat juga [`Shape.office_interop_shape_id`](/slides/python-net/id/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/id/aspose.slides.ink/ink/office_interop_shape_id/) | Mengembalikan pengenal unik berskala slide yang tetap konstan selama masa hidup shape dan<br/>            memungkinkan PowerPoint atau kode interop mereferensikan shape secara andal dari mana saja dalam dokumen.<br/>            **Baca-saja** **int**.<br/>            Lihat juga [`Shape.unique_id`](/slides/python-net/id/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/id/aspose.slides.ink/ink/alternative_text/) | Mengembalikan atau mengatur teks alternatif yang terkait dengan shape.<br/>            **Baca/tulis** **str**. |
| [`alternative_text_title`](/slides/python-net/id/aspose.slides.ink/ink/alternative_text_title/) | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan shape.<br/>            **Baca/tulis** **str**. |
| [`name`](/slides/python-net/id/aspose.slides.ink/ink/name/) | Mengembalikan atau mengatur nama shape.<br/>            Tidak boleh None. Gunakan string kosong jika diperlukan.<br/>            **Baca/tulis** **str**. |
| [`is_decorative`](/slides/python-net/id/aspose.slides.ink/ink/is_decorative/) | Mengambil atau mengatur opsi 'Mark as decorative'<br/>            **Baca/tulis** **bool**. |
| [`shape_lock`](/slides/python-net/id/aspose.slides.ink/ink/shape_lock/) | Mengembalikan kunci shape.<br/>            **Baca-saja** [`IGraphicalObjectLock`](/slides/python-net/id/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/id/aspose.slides.ink/ink/is_grouped/) | Menentukan apakah shape dikelompokkan.<br/>            **Baca-saja** **bool**. |
| [`parent_group`](/slides/python-net/id/aspose.slides.ink/ink/parent_group/) | Mengembalikan objek GroupShape induk jika shape dikelompokkan. Jika tidak, mengembalikan None.<br/>            **Baca-saja** [`IGroupShape`](/slides/python-net/id/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/id/aspose.slides.ink/ink/slide/) | Mengembalikan slide induk dari shape.<br/>            **Baca-saja** [`IBaseSlide`](/slides/python-net/id/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/id/aspose.slides.ink/ink/presentation/) | Mengembalikan presentasi induk dari slide.<br/>            **Baca-saja** [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/id/aspose.slides.ink/ink/graphical_object_lock/) | Mengembalikan kunci shape.<br/>            **Baca-saja** [`IGraphicalObjectLock`](/slides/python-net/id/aspose.slides/igraphicalobjectlock). |
| [`traces`](/slides/python-net/id/aspose.slides.ink/ink/traces/) | Mengambil semua jejak yang terdapat dalam elemen IInk [`IInkTrace`](/slides/python-net/id/aspose.slides.ink/iinktrace).<br/>            **Baca-saja**. |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`get_image(self)`](/slides/python-net/id/aspose.slides.ink/ink/get_image/#) | Mengembalikan thumbnail shape.<br/>            Tipe batas thumbnail shape ShapeThumbnailBounds.Shape digunakan secara default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/id/aspose.slides.ink/ink/get_image/#shapethumbnailbounds-float-float) | Mengembalikan thumbnail shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/id/aspose.slides.ink/ink/write_as_svg/#iorawiobase) | Menyimpan konten Shape sebagai file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/id/aspose.slides.ink/ink/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Menyimpan konten Shape sebagai file SVG. |
| [`remove_placeholder(self)`](/slides/python-net/id/aspose.slides.ink/ink/remove_placeholder/#) | Mendefinisikan bahwa shape ini bukan placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/id/aspose.slides.ink/ink/add_placeholder/#iplaceholder) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [`get_base_placeholder(self)`](/slides/python-net/id/aspose.slides.ink/ink/get_base_placeholder/#) | Mengembalikan shape placeholder dasar (shape dari tata letak dan/atau master slide yang diwarisi oleh shape saat ini).<br/>            Mengembalikan None jika shape saat ini tidak diwarisi. |
| [`get_visual_bounds(self)`](/slides/python-net/id/aspose.slides.ink/ink/get_visual_bounds/#) | Mengambil batas visual shape yang dihitung dari konten yang dirender. |
| [`register_ink_effect_image(effect_type, image)`](/slides/python-net/id/aspose.slides.ink/ink/register_ink_effect_image/#inkeffecttype-iimage) | Mendaftarkan gambar ke koleksi gambar kustom yang digunakan untuk mensimulasikan efek visual untuk kuas tinta.<br/>            Gambar-gambar ini digunakan saat merender tinta dengan nilai [`InkEffectType`](/slides/python-net/id/aspose.slides.ink/inkeffecttype) tertentu,<br/>            seperti Galaxy, Rainbow, dll. Dengan menyediakan gambar Anda sendiri, Anda dapat mengontrol tampilan setiap efek tinta. |
| [`unregister_ink_effect_image(effect_type)`](/slides/python-net/id/aspose.slides.ink/ink/unregister_ink_effect_image/#inkeffecttype) | Membatalkan pendaftaran gambar dari koleksi gambar kustom yang digunakan untuk mensimulasikan efek visual untuk kuas tinta<br/>            gambar yang sebelumnya terdaftar melalui **Aspose.Slides.Ink.Ink.RegisterInkEffectImage(Aspose.Slides.Ink.InkEffectType,Aspose.Slide**. |

### Lihat Juga
* kelas [`GraphicalObject`](/slides/python-net/id/aspose.slides/graphicalobject)
* kelas [`Ink`](/slides/python-net/id/aspose.slides.ink/ink)
* kelas [`Shape`](/slides/python-net/id/aspose.slides/shape)
* modul [`aspose.slides.ink`](/slides/python-net/id/aspose.slides.ink)
* pustaka [`Aspose.Slides`](/slides/python-net)