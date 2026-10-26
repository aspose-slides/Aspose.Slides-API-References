---
title: GraphicalObject class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/graphicalobject/
---
## GraphicalObject kelas

Represents abstract graphical object.

**Inheritance:**[`GraphicalObject`](/slides/python-net/id/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/id/aspose.slides/shape)

The GraphicalObject type exposes the following members:

## Properti

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/id/aspose.slides/graphicalobject/is_text_holder/) | Menentukan apakah bentuk merupakan TextHolder_PPT.<br/>            Read-only **bool**. |
| [`placeholder`](/slides/python-net/id/aspose.slides/graphicalobject/placeholder/) | Mengembalikan placeholder untuk sebuah shape. Mengembalikan None jika shape tidak memiliki placeholder.<br/>            Read-only [`IPlaceholder`](/slides/python-net/id/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/id/aspose.slides/graphicalobject/custom_data/) | Mengembalikan data khusus shape.<br/>            Read-only [`ICustomData`](/slides/python-net/id/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/id/aspose.slides/graphicalobject/raw_frame/) | Mengembalikan atau mengatur properti frame shape mentah.<br/>            Read/write [`IShapeFrame`](/slides/python-net/id/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/id/aspose.slides/graphicalobject/frame/) | Mengembalikan atau mengatur properti frame shape.<br/>            Read/write [`IShapeFrame`](/slides/python-net/id/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/id/aspose.slides/graphicalobject/line_format/) | Mengembalikan objek LineFormat yang berisi properti pemformatan garis untuk sebuah shape.<br/>            Catatan: dapat mengembalikan None untuk jenis shape tertentu yang tidak memiliki properti garis.<br/>            Read-only [`ILineFormat`](/slides/python-net/id/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/id/aspose.slides/graphicalobject/three_d_format/) | Mengembalikan objek ThreeDFormat yang berisi properti efek 3d untuk sebuah shape.<br/>            Catatan: dapat mengembalikan None untuk jenis shape tertentu yang tidak memiliki properti 3d.<br/>            Read-only [`IThreeDFormat`](/slides/python-net/id/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/id/aspose.slides/graphicalobject/effect_format/) | Mengembalikan objek EffectFormat yang berisi efek piksel yang diterapkan pada sebuah shape.<br/>            Catatan: dapat mengembalikan None untuk jenis shape tertentu yang tidak memiliki properti efek.<br/>            Read-only [`IEffectFormat`](/slides/python-net/id/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/id/aspose.slides/graphicalobject/fill_format/) | Mengembalikan objek FillFormat yang berisi properti pemformatan isian untuk sebuah shape.<br/>            Catatan: dapat mengembalikan None untuk jenis shape tertentu yang tidak memiliki properti isian.<br/>            Read-only [`IFillFormat`](/slides/python-net/id/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/id/aspose.slides/graphicalobject/hyperlink_click/) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse.<br/>            Read/write [`IHyperlink`](/slides/python-net/id/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/id/aspose.slides/graphicalobject/hyperlink_mouse_over/) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk hover mouse.<br/>            Read/write [`IHyperlink`](/slides/python-net/id/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/id/aspose.slides/graphicalobject/hyperlink_manager/) | Mengembalikan manajer hyperlink.<br/>            Read-only [`IHyperlinkManager`](/slides/python-net/id/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/id/aspose.slides/graphicalobject/hidden/) | Menentukan apakah shape tersembunyi.<br/>            Read/write **bool**. |
| [`z_order_position`](/slides/python-net/id/aspose.slides/graphicalobject/z_order_position/) | Mengembalikan posisi sebuah shape dalam urutan z.<br/>            Shapes[0] mengembalikan shape di bagian belakang urutan z,<br/>            dan Shapes[Shapes.Count - 1] mengembalikan shape di bagian depan urutan z.<br/>            Read-only **int**. |
| [`connection_site_count`](/slides/python-net/id/aspose.slides/graphicalobject/connection_site_count/) | Mengembalikan jumlah titik koneksi pada shape.<br/>            Read-only **int**. |
| [`rotation`](/slides/python-net/id/aspose.slides/graphicalobject/rotation/) | Mengembalikan atau mengatur jumlah derajat rotasi shape yang ditentukan sekitar sumbu z.<br/>            Nilai positif menunjukkan rotasi searah jam; nilai negatif menunjukkan rotasi berlawanan arah jam.<br/>            Read/write **float**. |
| [`x`](/slides/python-net/id/aspose.slides/graphicalobject/x/) | Mengambil atau mengatur koordinat x sudut kiri-atas shape, diukur dalam poin.<br/>            Read/write **float**. |
| [`y`](/slides/python-net/id/aspose.slides/graphicalobject/y/) | Mengambil atau mengatur koordinat y sudut kiri-atas shape, diukur dalam poin.<br/>            Read/write **float**. |
| [`width`](/slides/python-net/id/aspose.slides/graphicalobject/width/) | Mengambil atau mengatur lebar shape, diukur dalam poin.<br/>            Read/write **float**. |
| [`height`](/slides/python-net/id/aspose.slides/graphicalobject/height/) | Mengambil atau mengatur tinggi shape, diukur dalam poin.<br/>            Read/write **float**. |
| [`black_white_mode`](/slides/python-net/id/aspose.slides/graphicalobject/black_white_mode/) | Properti menentukan bagaimana shape akan ditampilkan dalam mode tampilan hitam-putih.<br/>            Read/write [`BlackWhiteMode`](/slides/python-net/id/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/id/aspose.slides/graphicalobject/unique_id/) | Mengembalikan pengenal internal yang berskala presentasi yang dimaksudkan untuk digunakan oleh add-in atau kode lainnya.<br/>            Karena nilai ini dapat dipilih ulang oleh pengguna atau secara programatik, itu tidak boleh diperlakukan<br/>            sebagai kunci unik yang persisten.<br/>            Read-only **int**.<br/>            Lihat juga [`Shape.office_interop_shape_id`](/slides/python-net/id/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/id/aspose.slides/graphicalobject/office_interop_shape_id/) | Mengembalikan pengenal unik berskala slide yang tetap konstan selama masa hidup shape dan<br/>            memungkinkan PowerPoint atau kode interop merujuk shape dengan andal dari mana saja dalam dokumen.<br/>            Read-only **int**.<br/>            Lihat juga [`Shape.unique_id`](/slides/python-net/id/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/id/aspose.slides/graphicalobject/alternative_text/) | Mengembalikan atau mengatur teks alternatif yang terkait dengan shape.<br/>            Read/write **str**. |
| [`alternative_text_title`](/slides/python-net/id/aspose.slides/graphicalobject/alternative_text_title/) | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan shape.<br/>            Read/write **str**. |
| [`name`](/slides/python-net/id/aspose.slides/graphicalobject/name/) | Mengembalikan atau mengatur nama shape.<br/>            Harus tidak None. Gunakan string kosong jika diperlukan.<br/>            Read/write **str**. |
| [`is_decorative`](/slides/python-net/id/aspose.slides/graphicalobject/is_decorative/) | Mengambil atau mengatur opsi 'Mark as decorative'<br/>            Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/id/aspose.slides/graphicalobject/shape_lock/) | Mengembalikan kunci shape.<br/>            Read-only [`IGraphicalObjectLock`](/slides/python-net/id/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/id/aspose.slides/graphicalobject/is_grouped/) | Menentukan apakah shape dikelompokkan.<br/>            Read-only **bool**. |
| [`parent_group`](/slides/python-net/id/aspose.slides/graphicalobject/parent_group/) | Mengembalikan objek GroupShape induk jika shape dikelompokkan. Jika tidak, mengembalikan None.<br/>            Read-only [`IGroupShape`](/slides/python-net/id/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/id/aspose.slides/graphicalobject/slide/) | Mengembalikan slide induk dari sebuah shape.<br/>            Read-only [`IBaseSlide`](/slides/python-net/id/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/id/aspose.slides/graphicalobject/presentation/) | Mengembalikan presentasi induk dari sebuah slide.<br/>            Read-only [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/id/aspose.slides/graphicalobject/graphical_object_lock/) | Mengembalikan kunci shape.<br/>            Read-only [`IGraphicalObjectLock`](/slides/python-net/id/aspose.slides/igraphicalobjectlock). |

## Metode

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/id/aspose.slides/graphicalobject/get_image/#) | Mengembalikan thumbnail shape.<br/>            Tipe batas thumbnail ShapeThumbnailBounds.Shape digunakan secara default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/id/aspose.slides/graphicalobject/get_image/#shapethumbnailbounds-float-float) | Mengembalikan thumbnail shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/id/aspose.slides/graphicalobject/write_as_svg/#iorawiobase) | Menyimpan konten Shape sebagai berkas SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/id/aspose.slides/graphicalobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Menyimpan konten Shape sebagai berkas SVG. |
| [`remove_placeholder(self)`](/slides/python-net/id/aspose.slides/graphicalobject/remove_placeholder/#) | Mendefinisikan bahwa shape ini bukan placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/id/aspose.slides/graphicalobject/add_placeholder/#iplaceholder) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [`get_base_placeholder(self)`](/slides/python-net/id/aspose.slides/graphicalobject/get_base_placeholder/#) | Mengembalikan shape placeholder dasar (shape dari layout dan/atau master slide yang diwarisi oleh shape saat ini).<br/>            Mengembalikan None jika shape saat ini tidak diwarisi. |
| [`get_visual_bounds(self)`](/slides/python-net/id/aspose.slides/graphicalobject/get_visual_bounds/#) | Mengambil batas visual shape yang dihitung dari konten yang dirender. |

### Lihat Juga
* kelas [`GraphicalObject`](/slides/python-net/id/aspose.slides/graphicalobject)
* kelas [`Shape`](/slides/python-net/id/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)