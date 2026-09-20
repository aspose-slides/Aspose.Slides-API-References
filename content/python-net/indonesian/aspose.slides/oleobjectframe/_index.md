---
title: OleObjectFrame class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/oleobjectframe/
---
## OleObjectFrame kelas

Mewakili objek OLE pada slide.

**Pewarisan:**[`OleObjectFrame`](/slides/python-net/id/aspose.slides/oleobjectframe) → [`GraphicalObject`](/slides/python-net/id/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/id/aspose.slides/shape)

The OleObjectFrame type exposes the following members:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`is_text_holder`](/slides/python-net/id/aspose.slides/oleobjectframe/is_text_holder/) | Menentukan apakah shape adalah TextHolder_PPT.<br/>            Baca-saja **bool**. |
| [`placeholder`](/slides/python-net/id/aspose.slides/oleobjectframe/placeholder/) | Mengembalikan placeholder untuk shape. Mengembalikan None jika shape tidak memiliki placeholder.<br/>            Baca-saja [`IPlaceholder`](/slides/python-net/id/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/id/aspose.slides/oleobjectframe/custom_data/) | Mengembalikan data khusus shape.<br/>            Baca-saja [`ICustomData`](/slides/python-net/id/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/id/aspose.slides/oleobjectframe/raw_frame/) | Mengembalikan atau mengatur properti frame shape mentah.<br/>            Baca/tulis [`IShapeFrame`](/slides/python-net/id/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/id/aspose.slides/oleobjectframe/frame/) | Mengembalikan atau mengatur properti frame shape.<br/>            Baca/tulis [`IShapeFrame`](/slides/python-net/id/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/id/aspose.slides/oleobjectframe/line_format/) | Mengembalikan objek LineFormat yang berisi properti pemformatan garis untuk shape.<br/>            Catatan: dapat mengembalikan None untuk beberapa jenis shape yang tidak memiliki properti garis.<br/>            Baca-saja [`ILineFormat`](/slides/python-net/id/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/id/aspose.slides/oleobjectframe/three_d_format/) | Mengembalikan objek ThreeDFormat yang berisi properti efek 3d untuk shape.<br/>            Catatan: dapat mengembalikan None untuk beberapa jenis shape yang tidak memiliki properti 3d.<br/>            Baca-saja [`IThreeDFormat`](/slides/python-net/id/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/id/aspose.slides/oleobjectframe/effect_format/) | Mengembalikan objek EffectFormat yang berisi efek piksel yang diterapkan pada shape.<br/>            Catatan: dapat mengembalikan None untuk beberapa jenis shape yang tidak memiliki properti efek.<br/>            Baca-saja [`IEffectFormat`](/slides/python-net/id/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/id/aspose.slides/oleobjectframe/fill_format/) | Mengembalikan objek FillFormat yang berisi properti pemformatan isi untuk shape.<br/>            Catatan: dapat mengembalikan None untuk beberapa jenis shape yang tidak memiliki properti isi.<br/>            Baca-saja [`IFillFormat`](/slides/python-net/id/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/id/aspose.slides/oleobjectframe/hyperlink_click/) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse.<br/>            Baca/tulis [`IHyperlink`](/slides/python-net/id/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/id/aspose.slides/oleobjectframe/hyperlink_mouse_over/) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk hover mouse.<br/>            Baca/tulis [`IHyperlink`](/slides/python-net/id/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/id/aspose.slides/oleobjectframe/hyperlink_manager/) | Mengembalikan pengelola hyperlink.<br/>            Baca-saja [`IHyperlinkManager`](/slides/python-net/id/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/id/aspose.slides/oleobjectframe/hidden/) | Menentukan apakah shape disembunyikan.<br/>            Baca/tulis **bool**. |
| [`z_order_position`](/slides/python-net/id/aspose.slides/oleobjectframe/z_order_position/) | Mengembalikan posisi shape dalam urutan z.<br/>            Shapes[0] mengembalikan shape di bagian belakang urutan z,<br/>            dan Shapes[Shapes.Count - 1] mengembalikan shape di bagian depan urutan z.<br/>            Baca-saja **int**. |
| [`connection_site_count`](/slides/python-net/id/aspose.slides/oleobjectframe/connection_site_count/) | Mengembalikan jumlah titik koneksi pada shape.<br/>            Baca-saja **int**. |
| [`rotation`](/slides/python-net/id/aspose.slides/oleobjectframe/rotation/) | Mengembalikan atau mengatur jumlah derajat rotasi shape yang ditentukan sekitar sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam.<br/>            Baca/tulis **float**. |
| [`x`](/slides/python-net/id/aspose.slides/oleobjectframe/x/) | Mendapatkan atau mengatur koordinat x sudut kiri atas shape, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`y`](/slides/python-net/id/aspose.slides/oleobjectframe/y/) | Mendapatkan atau mengatur koordinat y sudut kiri atas shape, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`width`](/slides/python-net/id/aspose.slides/oleobjectframe/width/) | Mendapatkan atau mengatur lebar shape, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`height`](/slides/python-net/id/aspose.slides/oleobjectframe/height/) | Mendapatkan atau mengatur tinggi shape, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`black_white_mode`](/slides/python-net/id/aspose.slides/oleobjectframe/black_white_mode/) | Properti menentukan bagaimana shape akan dirender dalam mode tampilan hitam-putih.<br/>            Baca/tulis [`BlackWhiteMode`](/slides/python-net/id/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/id/aspose.slides/oleobjectframe/unique_id/) | Mengembalikan pengidentifikasi internal yang berskala presentasi yang ditujukan untuk penggunaan oleh add-in atau kode lain.<br/>            Karena nilai ini dapat ditetapkan ulang oleh pengguna atau secara programatik, nilai ini tidak boleh diperlakukan sebagai kunci unik yang persisten.<br/>            Baca-saja **int**.<br/>            Lihat juga [`Shape.office_interop_shape_id`](/slides/python-net/id/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/id/aspose.slides/oleobjectframe/office_interop_shape_id/) | Mengembalikan pengidentifikasi unik berskala slide yang tetap konstan selama masa hidup shape dan memungkinkan PowerPoint atau kode interop merujuk shape secara andal dari mana saja dalam dokumen.<br/>            Baca-saja **int**.<br/>            Lihat juga [`Shape.unique_id`](/slides/python-net/id/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/id/aspose.slides/oleobjectframe/alternative_text/) | Mengembalikan atau mengatur teks alternatif yang terkait dengan shape.<br/>            Baca/tulis **str**. |
| [`alternative_text_title`](/slides/python-net/id/aspose.slides/oleobjectframe/alternative_text_title/) | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan shape.<br/>            Baca/tulis **str**. |
| [`name`](/slides/python-net/id/aspose.slides/oleobjectframe/name/) | Mengembalikan atau mengatur nama shape.<br/>            Harus tidak None. Gunakan nilai string kosong jika diperlukan.<br/>            Baca/tulis **str**. |
| [`is_decorative`](/slides/python-net/id/aspose.slides/oleobjectframe/is_decorative/) | Mendapatkan atau mengatur opsi 'Mark as decorative'<br/>            Baca/tulis **bool**. |
| [`shape_lock`](/slides/python-net/id/aspose.slides/oleobjectframe/shape_lock/) | Mengembalikan kunci shape.<br/>            Baca-saja [`IGraphicalObjectLock`](/slides/python-net/id/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/id/aspose.slides/oleobjectframe/is_grouped/) | Menentukan apakah shape dikelompokkan.<br/>            Baca-saja **bool**. |
| [`parent_group`](/slides/python-net/id/aspose.slides/oleobjectframe/parent_group/) | Mengembalikan objek GroupShape induk jika shape dikelompokkan. Jika tidak, mengembalikan None.<br/>            Baca-saja [`IGroupShape`](/slides/python-net/id/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/id/aspose.slides/oleobjectframe/slide/) | Mengembalikan slide induk dari shape.<br/>            Baca-saja [`IBaseSlide`](/slides/python-net/id/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/id/aspose.slides/oleobjectframe/presentation/) | Mengembalikan presentasi induk dari slide.<br/>            Baca-saja [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/id/aspose.slides/oleobjectframe/graphical_object_lock/) | Mengembalikan kunci shape.<br/>            Baca-saja [`IGraphicalObjectLock`](/slides/python-net/id/aspose.slides/igraphicalobjectlock). |
| [`substitute_picture_format`](/slides/python-net/id/aspose.slides/oleobjectframe/substitute_picture_format/) | Mengembalikan objek properti isian gambar OleObject.<br/>            Baca-saja [`IPictureFillFormat`](/slides/python-net/id/aspose.slides/ipicturefillformat). |
| [`substitute_picture_title`](/slides/python-net/id/aspose.slides/oleobjectframe/substitute_picture_title/) | Mengembalikan atau mengatur judul untuk ikon OleObject.<br/>            Baca/tulis **str**. |
| [`object_name`](/slides/python-net/id/aspose.slides/oleobjectframe/object_name/) | Mengembalikan atau mengatur nama objek.<br/>            Baca/tulis **str**. |
| [`object_prog_id`](/slides/python-net/id/aspose.slides/oleobjectframe/object_prog_id/) | Mengembalikan ProgID objek.<br/>            Baca-saja **str**. |
| [`link_file_name`](/slides/python-net/id/aspose.slides/oleobjectframe/link_file_name/) | Mengembalikan jalur lengkap ke file yang ditautkan. Nama file pendek akan digunakan.<br/>            Baca-saja **str**. |
| [`link_path_long`](/slides/python-net/id/aspose.slides/oleobjectframe/link_path_long/) | Mengembalikan jalur lengkap ke file yang ditautkan. Nama file panjang akan digunakan.<br/>            Baca/tulis **str**. |
| [`link_path_relative`](/slides/python-net/id/aspose.slides/oleobjectframe/link_path_relative/) | Mengembalikan jalur relatif ke file yang ditautkan jika ada, jika tidak mengembalikan string kosong.<br/>            Baca-saja **str**. |
| [`embedded_file_label`](/slides/python-net/id/aspose.slides/oleobjectframe/embedded_file_label/) | Mengembalikan nama file objek OLE yang disematkan |
| [`embedded_file_name`](/slides/python-net/id/aspose.slides/oleobjectframe/embedded_file_name/) | Mengembalikan jalur objek OLE yang disematkan |
| [`embedded_data`](/slides/python-net/id/aspose.slides/oleobjectframe/embedded_data/) | Mendapatkan atau mengatur informasi tentang data OLE yang disematkan.<br/>            Baca/tulis [`IOleEmbeddedDataInfo`](/slides/python-net/id/aspose.slides/ioleembeddeddatainfo). |
| [`is_object_icon`](/slides/python-net/id/aspose.slides/oleobjectframe/is_object_icon/) | Menentukan apakah objek terlihat sebagai ikon.<br/>            Baca/tulis **bool**. |
| [`is_object_link`](/slides/python-net/id/aspose.slides/oleobjectframe/is_object_link/) | Menentukan apakah objek ditautkan ke file eksternal.<br/>            Baca-saja **bool**. |
| [`update_automatic`](/slides/python-net/id/aspose.slides/oleobjectframe/update_automatic/) | Menentukan apakah objek yang ditautkan dan disematkan diperbarui secara otomatis saat presentasi dibuka atau dicetak.<br/>            Baca/tulis **bool**. |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`get_image(self)`](/slides/python-net/id/aspose.slides/oleobjectframe/get_image/#) | Mengembalikan thumbnail shape.<br/>            Tipe batas thumbnail shape ShapeThumbnailBounds.Shape digunakan secara default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/id/aspose.slides/oleobjectframe/get_image/#shapethumbnailbounds-float-float) | Mengembalikan thumbnail shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/id/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase) | Menyimpan konten Shape sebagai file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/id/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Menyimpan konten Shape sebagai file SVG. |
| [`remove_placeholder(self)`](/slides/python-net/id/aspose.slides/oleobjectframe/remove_placeholder/#) | Mendefinisikan bahwa shape ini bukan placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/id/aspose.slides/oleobjectframe/add_placeholder/#iplaceholder) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [`get_base_placeholder(self)`](/slides/python-net/id/aspose.slides/oleobjectframe/get_base_placeholder/#) | Mengembalikan shape placeholder dasar (shape dari tata letak dan/atau slide master yang diwarisi oleh shape saat ini).<br/>            None dikembalikan jika shape saat ini tidak diwarisi. |
| [`get_visual_bounds(self)`](/slides/python-net/id/aspose.slides/oleobjectframe/get_visual_bounds/#) | Mendapatkan batas visual shape yang dihitung dari konten yang dirender. |
| [`set_embedded_data(self, embedded_data)`](/slides/python-net/id/aspose.slides/oleobjectframe/set_embedded_data/#ioleembeddeddatainfo) | Mengatur informasi tentang data OLE yang disematkan.<br/>            <br/>            Metode ini mengubah properti objek untuk mencerminkan data baru dan mengatur flag IsObjectLink menjadi false, menunjukkan bahwa objek OLE disematkan. |

### Lihat Juga
* kelas [`GraphicalObject`](/slides/python-net/id/aspose.slides/graphicalobject)
* kelas [`OleObjectFrame`](/slides/python-net/id/aspose.slides/oleobjectframe)
* kelas [`Shape`](/slides/python-net/id/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)