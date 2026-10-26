---
title: SmartArtShape class
second_title: Aspose.Slides untuk Python via .NET API Reference
description: 
type: docs
url: /id/aspose.slides.smartart/smartartshape/
---
## SmartArtShape kelas

Mewakili bentuk SmartArt

**Pewarisan:**[`SmartArtShape`](/slides/python-net/id/aspose.slides.smartart/smartartshape) → [`GeometryShape`](/slides/python-net/id/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/id/aspose.slides/shape)

Tipe SmartArtShape menyediakan anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`is_text_holder`](/slides/python-net/id/aspose.slides.smartart/smartartshape/is_text_holder/) | Menentukan apakah shape adalah TextHolder_PPT.<br/>            Baca-saja **bool**. |
| [`placeholder`](/slides/python-net/id/aspose.slides.smartart/smartartshape/placeholder/) | Mengembalikan placeholder untuk shape. Mengembalikan None jika shape tidak memiliki placeholder.<br/>            Baca-saja [`IPlaceholder`](/slides/python-net/id/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/id/aspose.slides.smartart/smartartshape/custom_data/) | Mengembalikan data khusus shape.<br/>            Baca-saja [`ICustomData`](/slides/python-net/id/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/id/aspose.slides.smartart/smartartshape/raw_frame/) | Mengembalikan atau mengatur properti frame shape mentah.<br/>            Baca/tulis [`IShapeFrame`](/slides/python-net/id/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/id/aspose.slides.smartart/smartartshape/frame/) | Mengembalikan atau mengatur properti frame shape.<br/>            Baca/tulis [`IShapeFrame`](/slides/python-net/id/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/id/aspose.slides.smartart/smartartshape/line_format/) | Mengembalikan objek LineFormat yang berisi properti pemformatan garis untuk shape.<br/>            Catatan: dapat mengembalikan None untuk tipe shape tertentu yang tidak memiliki properti garis.<br/>            Baca-saja [`ILineFormat`](/slides/python-net/id/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/id/aspose.slides.smartart/smartartshape/three_d_format/) | Mengembalikan objek ThreeDFormat yang berisi properti efek 3d untuk shape.<br/>            Catatan: dapat mengembalikan None untuk tipe shape tertentu yang tidak memiliki properti 3d.<br/>            Baca-saja [`IThreeDFormat`](/slides/python-net/id/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/id/aspose.slides.smartart/smartartshape/effect_format/) | Mengembalikan objek EffectFormat yang berisi efek piksel yang diterapkan pada shape.<br/>            Catatan: dapat mengembalikan None untuk tipe shape tertentu yang tidak memiliki properti efek.<br/>            Baca-saja [`IEffectFormat`](/slides/python-net/id/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/id/aspose.slides.smartart/smartartshape/fill_format/) | Mengembalikan objek FillFormat yang berisi properti pemformatan isi untuk shape.<br/>            Catatan: dapat mengembalikan None untuk tipe shape tertentu yang tidak memiliki properti isi.<br/>            Baca-saja [`IFillFormat`](/slides/python-net/id/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/id/aspose.slides.smartart/smartartshape/hyperlink_click/) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse.<br/>            Baca/tulis [`IHyperlink`](/slides/python-net/id/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/id/aspose.slides.smartart/smartartshape/hyperlink_mouse_over/) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk hover mouse.<br/>            Baca/tulis [`IHyperlink`](/slides/python-net/id/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/id/aspose.slides.smartart/smartartshape/hyperlink_manager/) | Mengembalikan manajer hyperlink.<br/>            Baca-saja [`IHyperlinkManager`](/slides/python-net/id/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/id/aspose.slides.smartart/smartartshape/hidden/) | Menentukan apakah shape disembunyikan.<br/>            Baca/tulis **bool**. |
| [`z_order_position`](/slides/python-net/id/aspose.slides.smartart/smartartshape/z_order_position/) | Mengembalikan posisi shape dalam urutan-z.<br/>            Shapes[0] mengembalikan shape paling belakang dalam urutan-z,<br/>            dan Shapes[Shapes.Count - 1] mengembalikan shape paling depan dalam urutan-z.<br/>            Baca-saja **int**. |
| [`connection_site_count`](/slides/python-net/id/aspose.slides.smartart/smartartshape/connection_site_count/) | Mengembalikan jumlah situs koneksi pada shape.<br/>            Baca-saja **int**. |
| [`rotation`](/slides/python-net/id/aspose.slides.smartart/smartartshape/rotation/) | Mengembalikan atau mengatur jumlah derajat rotasi shape di sekitar sumbu z.<br/>            Nilai positif menandakan rotasi searah jarum jam; nilai negatif menandakan rotasi berlawanan arah jarum jam.<br/>            Baca/tulis **float**. |
| [`x`](/slides/python-net/id/aspose.slides.smartart/smartartshape/x/) | Mengambil atau mengatur koordinat x sudut kiri-atas shape, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`y`](/slides/python-net/id/aspose.slides.smartart/smartartshape/y/) | Mengambil atau mengatur koordinat y sudut kiri-atas shape, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`width`](/slides/python-net/id/aspose.slides.smartart/smartartshape/width/) | Mengambil atau mengatur lebar shape, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`height`](/slides/python-net/id/aspose.slides.smartart/smartartshape/height/) | Mengambil atau mengatur tinggi shape, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`black_white_mode`](/slides/python-net/id/aspose.slides.smartart/smartartshape/black_white_mode/) | Properti menentukan bagaimana shape akan ditampilkan dalam mode tampilan hitam-putih..<br/>            Baca/tulis [`BlackWhiteMode`](/slides/python-net/id/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/id/aspose.slides.smartart/smartartshape/unique_id/) | Mengembalikan pengenal internal yang berskala presentasi, dimaksudkan untuk penggunaan oleh add-in atau kode lain.<br/>            Karena nilai ini dapat ditetapkan ulang oleh pengguna atau secara programatik, tidak boleh diperlakukan sebagai kunci unik yang persisten.<br/>            Baca-saja **int**.<br/>            Lihat juga [`Shape.office_interop_shape_id`](/slides/python-net/id/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/id/aspose.slides.smartart/smartartshape/office_interop_shape_id/) | Mengembalikan pengenal unik berskala slide yang tetap konstan selama masa hidup shape dan memungkinkan PowerPoint atau kode interop merujuk shape secara andal dari mana saja dalam dokumen.<br/>            Baca-saja **int**.<br/>            Lihat juga [`Shape.unique_id`](/slides/python-net/id/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/id/aspose.slides.smartart/smartartshape/alternative_text/) | Mengembalikan atau mengatur teks alternatif yang terkait dengan shape.<br/>            Baca/tulis **str**. |
| [`alternative_text_title`](/slides/python-net/id/aspose.slides.smartart/smartartshape/alternative_text_title/) | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan shape.<br/>            Baca/tulis **str**. |
| [`name`](/slides/python-net/id/aspose.slides.smartart/smartartshape/name/) | Mengembalikan atau mengatur nama shape.<br/>            Harus tidak None. Gunakan string kosong bila diperlukan.<br/>            Baca/tulis **str**. |
| [`is_decorative`](/slides/python-net/id/aspose.slides.smartart/smartartshape/is_decorative/) | Mengambil atau mengatur opsi 'Tandai sebagai dekoratif'<br/>            Baca/tulis **bool**. |
| [`shape_lock`](/slides/python-net/id/aspose.slides.smartart/smartartshape/shape_lock/) | Mengembalikan kunci shape.<br/>            Baca-saja [`IBaseShapeLock`](/slides/python-net/id/aspose.slides/ibaseshapelock). |
| [`is_grouped`](/slides/python-net/id/aspose.slides.smartart/smartartshape/is_grouped/) | Menentukan apakah shape dikelompokkan.<br/>            Baca-saja **bool**. |
| [`parent_group`](/slides/python-net/id/aspose.slides.smartart/smartartshape/parent_group/) | Mengembalikan objek GroupShape induk jika shape dikelompokkan. Jika tidak, mengembalikan None.<br/>            Baca-saja [`IGroupShape`](/slides/python-net/id/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/id/aspose.slides.smartart/smartartshape/slide/) | Mengembalikan slide induk dari shape.<br/>            Baca-saja [`IBaseSlide`](/slides/python-net/id/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/id/aspose.slides.smartart/smartartshape/presentation/) | Mengembalikan presentasi induk dari slide.<br/>            Baca-saja [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/id/aspose.slides.smartart/smartartshape/shape_style/) | Mengembalikan objek gaya shape.<br/>            Baca-saja [`IShapeStyle`](/slides/python-net/id/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/id/aspose.slides.smartart/smartartshape/shape_type/) | Mengembalikan atau mengatur tipe preset geometri.<br/>            Catatan: pada perubahan nilai semua nilai penyesuaian akan direset ke nilai default mereka.<br/>            Baca/tulis [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/id/aspose.slides.smartart/smartartshape/adjustments/) | Mengembalikan koleksi nilai penyesuaian shape.<br/>            Baca-saja [`IAdjustValueCollection`](/slides/python-net/id/aspose.slides/iadjustvaluecollection). |
| [`text_frame`](/slides/python-net/id/aspose.slides.smartart/smartartshape/text_frame/) | Mengembalikan teks shape SmartArt.<br/>            Baca-saja [`ITextFrame`](/slides/python-net/id/aspose.slides/itextframe). |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`get_image(self)`](/slides/python-net/id/aspose.slides.smartart/smartartshape/get_image/#) | Mengembalikan thumbnail shape.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type digunakan secara default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/id/aspose.slides.smartart/smartartshape/get_image/#shapethumbnailbounds-float-float) | Mengembalikan thumbnail shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/id/aspose.slides.smartart/smartartshape/write_as_svg/#iorawiobase) | Menyimpan konten Shape sebagai file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/id/aspose.slides.smartart/smartartshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Menyimpan konten Shape sebagai file SVG. |
| [`remove_placeholder(self)`](/slides/python-net/id/aspose.slides.smartart/smartartshape/remove_placeholder/#) | Menetapkan bahwa shape ini bukan placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/id/aspose.slides.smartart/smartartshape/add_placeholder/#iplaceholder) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [`get_base_placeholder(self)`](/slides/python-net/id/aspose.slides.smartart/smartartshape/get_base_placeholder/#) | Mengembalikan shape placeholder dasar (shape dari tata letak dan/atau master slide yang diwarisi oleh shape saat ini).<br/>            None dikembalikan jika shape saat ini tidak diwarisi. |
| [`get_visual_bounds(self)`](/slides/python-net/id/aspose.slides.smartart/smartartshape/get_visual_bounds/#) | Mengambil batas visual shape yang dihitung dari konten yang dirender. |
| [`get_geometry_paths(self)`](/slides/python-net/id/aspose.slides.smartart/smartartshape/get_geometry_paths/#) | Mengembalikan salinan jalur geometri shape. Koordinat relatif terhadap sudut kiri atas shape. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/id/aspose.slides.smartart/smartartshape/set_geometry_path/#igeometrypath) | Memperbarui geometri shape dari objek [`IGeometryPath`](/slides/python-net/id/aspose.slides/igeometrypath). Koordinat harus relatif terhadap sudut kiri<br/>            atas shape.<br/>            Mengubah tipe shape ([`GeometryShape.shape_type`](/slides/python-net/id/aspose.slides/geometryshape/shape_type)) menjadi [`ShapeType.CUSTOM`](/slides/python-net/id/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/id/aspose.slides.smartart/smartartshape/set_geometry_paths/#listigeometrypath) | Memperbarui geometri shape dari larik [`IGeometryPath`](/slides/python-net/id/aspose.slides/igeometrypath). Koordinat harus relatif terhadap sudut kiri<br/>            atas shape.<br/>            Mengubah tipe shape ([`GeometryShape.shape_type`](/slides/python-net/id/aspose.slides/geometryshape/shape_type)) menjadi [`ShapeType.CUSTOM`](/slides/python-net/id/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/id/aspose.slides.smartart/smartartshape/create_shape_elements/#) | Membuat dan mengembalikan larik elemen shape. |

### Lihat Juga
* kelas [`GeometryShape`](/slides/python-net/id/aspose.slides/geometryshape)
* kelas [`Shape`](/slides/python-net/id/aspose.slides/shape)
* kelas [`SmartArtShape`](/slides/python-net/id/aspose.slides.smartart/smartartshape)
* modul [`aspose.slides.smartart`](/slides/python-net/id/aspose.slides.smartart)
* perpustakaan [`Aspose.Slides`](/slides/python-net)