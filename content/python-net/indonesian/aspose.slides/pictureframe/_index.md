---
title: PictureFrame class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/pictureframe/
---
## Kelas PictureFrame

Mewakili sebuah frame dengan gambar di dalamnya.

**Pewarisan:**[`PictureFrame`](/slides/python-net/id/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/id/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/id/aspose.slides/shape)

Tipe PictureFrame mengekspos anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`is_text_holder`](/slides/python-net/id/aspose.slides/pictureframe/is_text_holder/) | Menentukan apakah shape adalah TextHolder_PPT.<br/>            Baca-saja **bool**. |
| [`placeholder`](/slides/python-net/id/aspose.slides/pictureframe/placeholder/) | Mengembalikan placeholder untuk sebuah shape. Mengembalikan None jika shape tidak memiliki placeholder.<br/>            Baca-saja [`IPlaceholder`](/slides/python-net/id/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/id/aspose.slides/pictureframe/custom_data/) | Mengembalikan data khusus shape.<br/>            Baca-saja [`ICustomData`](/slides/python-net/id/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/id/aspose.slides/pictureframe/raw_frame/) | Mengembalikan atau mengatur properti frame shape mentah.<br/>            Baca/tulis [`IShapeFrame`](/slides/python-net/id/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/id/aspose.slides/pictureframe/frame/) | Mengembalikan atau mengatur properti frame shape.<br/>            Baca/tulis [`IShapeFrame`](/slides/python-net/id/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/id/aspose.slides/pictureframe/line_format/) | Mengembalikan objek LineFormat yang berisi properti pemformatan garis untuk sebuah shape.<br/>            Catatan: dapat mengembalikan None untuk beberapa tipe shape yang tidak memiliki properti garis.<br/>            Baca-saja [`ILineFormat`](/slides/python-net/id/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/id/aspose.slides/pictureframe/three_d_format/) | Mengembalikan objek ThreeDFormat yang berisi properti efek 3d untuk sebuah shape.<br/>            Catatan: dapat mengembalikan None untuk beberapa tipe shape yang tidak memiliki properti 3d.<br/>            Baca-saja [`IThreeDFormat`](/slides/python-net/id/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/id/aspose.slides/pictureframe/effect_format/) | Mengembalikan objek EffectFormat yang berisi efek pixel yang diterapkan pada sebuah shape.<br/>            Catatan: dapat mengembalikan None untuk beberapa tipe shape yang tidak memiliki properti efek.<br/>            Baca-saja [`IEffectFormat`](/slides/python-net/id/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/id/aspose.slides/pictureframe/fill_format/) | Mengembalikan objek FillFormat yang berisi properti pemformatan isian untuk sebuah shape.<br/>            Catatan: dapat mengembalikan None untuk beberapa tipe shape yang tidak memiliki properti isian.<br/>            Baca-saja [`IFillFormat`](/slides/python-net/id/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/id/aspose.slides/pictureframe/hyperlink_click/) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse.<br/>            Baca/tulis [`IHyperlink`](/slides/python-net/id/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/id/aspose.slides/pictureframe/hyperlink_mouse_over/) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk hover mouse.<br/>            Baca/tulis [`IHyperlink`](/slides/python-net/id/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/id/aspose.slides/pictureframe/hyperlink_manager/) | Mengembalikan manajer hyperlink.<br/>            Baca-saja [`IHyperlinkManager`](/slides/python-net/id/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/id/aspose.slides/pictureframe/hidden/) | Menentukan apakah shape disembunyikan.<br/>            Baca/tulis **bool**. |
| [`z_order_position`](/slides/python-net/id/aspose.slides/pictureframe/z_order_position/) | Mengembalikan posisi sebuah shape dalam urutan z.<br/>            Shapes[0] mengembalikan shape di bagian belakang urutan z,<br/>            dan Shapes[Shapes.Count - 1] mengembalikan shape di bagian depan urutan z.<br/>            Baca-saja **int**. |
| [`connection_site_count`](/slides/python-net/id/aspose.slides/pictureframe/connection_site_count/) | Mengembalikan jumlah titik koneksi pada shape.<br/>            Baca-saja **int**. |
| [`rotation`](/slides/python-net/id/aspose.slides/pictureframe/rotation/) | Mengembalikan atau mengatur jumlah derajat rotasi shape sekitar sumbu z.<br/>            Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam.<br/>            Baca/tulis **float**. |
| [`x`](/slides/python-net/id/aspose.slides/pictureframe/x/) | Mengembalikan atau mengatur koordinat x sudut kiri atas shape, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`y`](/slides/python-net/id/aspose.slides/pictureframe/y/) | Mengembalikan atau mengatur koordinat y sudut kiri atas shape, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`width`](/slides/python-net/id/aspose.slides/pictureframe/width/) | Mengembalikan atau mengatur lebar shape, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`height`](/slides/python-net/id/aspose.slides/pictureframe/height/) | Mengembalikan atau mengatur tinggi shape, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`black_white_mode`](/slides/python-net/id/aspose.slides/pictureframe/black_white_mode/) | Properti menentukan bagaimana shape akan dirender dalam mode tampilan hitam-putih.<br/>            Baca/tulis [`BlackWhiteMode`](/slides/python-net/id/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/id/aspose.slides/pictureframe/unique_id/) | Mengembalikan pengenal internal berskala presentasi yang dimaksudkan untuk digunakan oleh add-in atau kode lain.<br/>            Karena nilai ini dapat ditetapkan ulang oleh pengguna atau secara programatis, jangan dianggap sebagai kunci unik yang persisten.<br/>            Baca-saja **int**.<br/>            Lihat juga [`Shape.office_interop_shape_id`](/slides/python-net/id/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/id/aspose.slides/pictureframe/office_interop_shape_id/) | Mengembalikan pengenal unik berskala slide yang tetap konstan selama masa hidup shape dan memungkinkan PowerPoint atau kode interop merujuk shape secara andal dari manapun dalam dokumen.<br/>            Baca-saja **int**.<br/>            Lihat juga [`Shape.unique_id`](/slides/python-net/id/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/id/aspose.slides/pictureframe/alternative_text/) | Mengembalikan atau mengatur teks alternatif yang terkait dengan sebuah shape.<br/>            Baca/tulis **str**. |
| [`alternative_text_title`](/slides/python-net/id/aspose.slides/pictureframe/alternative_text_title/) | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan sebuah shape.<br/>            Baca/tulis **str**. |
| [`name`](/slides/python-net/id/aspose.slides/pictureframe/name/) | Mengembalikan atau mengatur nama sebuah shape.<br/>            Harus tidak None. Gunakan string kosong bila diperlukan.<br/>            Baca/tulis **str**. |
| [`is_decorative`](/slides/python-net/id/aspose.slides/pictureframe/is_decorative/) | Mengatur opsi 'Tandai sebagai dekoratif'<br/>            Baca/tulis **bool**. |
| [`shape_lock`](/slides/python-net/id/aspose.slides/pictureframe/shape_lock/) | Mengembalikan kunci shape.<br/>            Baca-saja [`IPictureFrameLock`](/slides/python-net/id/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/id/aspose.slides/pictureframe/is_grouped/) | Menentukan apakah shape dikelompokkan.<br/>            Baca-saja **bool**. |
| [`parent_group`](/slides/python-net/id/aspose.slides/pictureframe/parent_group/) | Mengembalikan objek GroupShape induk jika shape dikelompokkan. Jika tidak, mengembalikan None.<br/>            Baca-saja [`IGroupShape`](/slides/python-net/id/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/id/aspose.slides/pictureframe/slide/) | Mengembalikan slide induk dari sebuah shape.<br/>            Baca-saja [`IBaseSlide`](/slides/python-net/id/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/id/aspose.slides/pictureframe/presentation/) | Mengembalikan presentasi induk dari sebuah slide.<br/>            Baca-saja [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/id/aspose.slides/pictureframe/shape_style/) | Mengembalikan objek gaya shape.<br/>            Baca-saja [`IShapeStyle`](/slides/python-net/id/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/id/aspose.slides/pictureframe/shape_type/) | Mengembalikan atau mengatur tipe AutoShape untuk PictureFrame.<br/>            Semua item yang diizinkan berada dalam set [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype), <br/>            kecuali semua jenis garis:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Baca/tulis [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/id/aspose.slides/pictureframe/adjustments/) | Mengembalikan koleksi nilai penyesuaian shape.<br/>            Baca-saja [`IAdjustValueCollection`](/slides/python-net/id/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/id/aspose.slides/pictureframe/picture_frame_lock/) | Mengembalikan kunci shape.<br/>            Baca-saja [`IPictureFrameLock`](/slides/python-net/id/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/id/aspose.slides/pictureframe/picture_format/) | Mengembalikan objek PictureFillFormat untuk frame gambar.<br/>            Baca-saja [`IPictureFillFormat`](/slides/python-net/id/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/id/aspose.slides/pictureframe/relative_scale_height/) | Mengembalikan atau mengatur skala tinggi (relatif terhadap ukuran gambar asli) dari frame gambar. Nilai 1.0 sesuai dengan 100%.<br/>            Baca/tulis **float**. |
| [`relative_scale_width`](/slides/python-net/id/aspose.slides/pictureframe/relative_scale_width/) | Mengembalikan atau mengatur skala lebar (relatif terhadap ukuran gambar asli) dari frame gambar. Nilai 1.0 sesuai dengan 100%.<br/>            Baca/tulis **float**. |
| [`is_cameo`](/slides/python-net/id/aspose.slides/pictureframe/is_cameo/) | Menentukan apakah PictureFrame adalah objek Cameo atau tidak.<br/>            Baca-saja **bool**. |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`get_image(self)`](/slides/python-net/id/aspose.slides/pictureframe/get_image/#) | Mengembalikan thumbnail shape.<br/>            Jenis batas thumbnail shape ShapeThumbnailBounds.Shape digunakan secara default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/id/aspose.slides/pictureframe/get_image/#shapethumbnailbounds-float-float) | Mengembalikan thumbnail shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/id/aspose.slides/pictureframe/write_as_svg/#iorawiobase) | Menyimpan konten Shape sebagai file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/id/aspose.slides/pictureframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Menyimpan konten Shape sebagai file SVG. |
| [`remove_placeholder(self)`](/slides/python-net/id/aspose.slides/pictureframe/remove_placeholder/#) | Mendefinisikan bahwa shape ini bukan placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/id/aspose.slides/pictureframe/add_placeholder/#iplaceholder) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [`get_base_placeholder(self)`](/slides/python-net/id/aspose.slides/pictureframe/get_base_placeholder/#) | Mengembalikan shape placeholder dasar (shape dari tata letak dan/atau slide master yang diwarisi oleh shape saat ini).<br/>            None dikembalikan jika shape saat ini tidak diwarisi. |
| [`get_visual_bounds(self)`](/slides/python-net/id/aspose.slides/pictureframe/get_visual_bounds/#) | Mendapatkan batas visual shape yang dihitung dari konten yang dirender. |
| [`get_geometry_paths(self)`](/slides/python-net/id/aspose.slides/pictureframe/get_geometry_paths/#) | Mengembalikan salinan jalur shape geometri. Koordinat relatif terhadap pojok kiri atas shape. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/id/aspose.slides/pictureframe/set_geometry_path/#igeometrypath) | Memperbarui geometri shape dari objek [`IGeometryPath`](/slides/python-net/id/aspose.slides/igeometrypath). Koordinat harus relatif terhadap kiri<br/>             atas shape.<br/>             Mengubah tipe shape ([`GeometryShape.shape_type`](/slides/python-net/id/aspose.slides/geometryshape/shape_type)) menjadi [`ShapeType.CUSTOM`](/slides/python-net/id/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/id/aspose.slides/pictureframe/set_geometry_paths/#listigeometrypath) | Memperbarui geometri shape dari array [`IGeometryPath`](/slides/python-net/id/aspose.slides/igeometrypath). Koordinat harus relatif terhadap kiri<br/>             atas shape.<br/>             Mengubah tipe shape ([`GeometryShape.shape_type`](/slides/python-net/id/aspose.slides/geometryshape/shape_type)) menjadi [`ShapeType.CUSTOM`](/slides/python-net/id/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/id/aspose.slides/pictureframe/create_shape_elements/#) | Membuat dan mengembalikan array elemen shape. |


### Lihat Juga
* kelas [`GeometryShape`](/slides/python-net/id/aspose.slides/geometryshape)
* kelas [`PictureFrame`](/slides/python-net/id/aspose.slides/pictureframe)
* kelas [`Shape`](/slides/python-net/id/aspose.slides/shape)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)