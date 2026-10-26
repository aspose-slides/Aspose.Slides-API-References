---
title: VideoFrame class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/videoframe/
---
## VideoFrame kelas

Represents a video clip on a slide.

**Warisan:**[`VideoFrame`](/slides/python-net/id/aspose.slides/videoframe) → [`PictureFrame`](/slides/python-net/id/aspose.slides/pictureframe) → [`GeometryShape`](/slides/python-net/id/aspose.slides/geometryshape) → [`Shape`](/slides/python-net/id/aspose.slides/shape)

The VideoFrame type exposes the following members:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`is_text_holder`](/slides/python-net/id/aspose.slides/videoframe/is_text_holder/) | Menentukan apakah shape adalah TextHolder_PPT.<br/>            Hanya-baca **bool**. |
| [`placeholder`](/slides/python-net/id/aspose.slides/videoframe/placeholder/) | Mengembalikan placeholder untuk sebuah shape. Mengembalikan None jika shape tidak memiliki placeholder.<br/>            Hanya-baca [`IPlaceholder`](/slides/python-net/id/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/id/aspose.slides/videoframe/custom_data/) | Mengembalikan data khusus shape.<br/>            Hanya-baca [`ICustomData`](/slides/python-net/id/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/id/aspose.slides/videoframe/raw_frame/) | Mengembalikan atau mengatur properti frame shape mentah.<br/>            Baca/tulis [`IShapeFrame`](/slides/python-net/id/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/id/aspose.slides/videoframe/frame/) | Mengembalikan atau mengatur properti frame shape.<br/>            Baca/tulis [`IShapeFrame`](/slides/python-net/id/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/id/aspose.slides/videoframe/line_format/) | Mengembalikan objek LineFormat yang berisi properti pemformatan garis untuk sebuah shape.<br/>            Catatan: dapat mengembalikan None untuk tipe shape tertentu yang tidak memiliki properti garis.<br/>            Hanya-baca [`ILineFormat`](/slides/python-net/id/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/id/aspose.slides/videoframe/three_d_format/) | Mengembalikan objek ThreeDFormat yang berisi properti efek 3d untuk sebuah shape.<br/>            Catatan: dapat mengembalikan None untuk tipe shape tertentu yang tidak memiliki properti 3d.<br/>            Hanya-baca [`IThreeDFormat`](/slides/python-net/id/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/id/aspose.slides/videoframe/effect_format/) | Mengembalikan objek EffectFormat yang berisi efek piksel yang diterapkan pada sebuah shape.<br/>            Catatan: dapat mengembalikan None untuk tipe shape tertentu yang tidak memiliki properti efek.<br/>            Hanya-baca [`IEffectFormat`](/slides/python-net/id/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/id/aspose.slides/videoframe/fill_format/) | Mengembalikan objek FillFormat yang berisi properti pemformatan isi untuk sebuah shape.<br/>            Catatan: dapat mengembalikan None untuk tipe shape tertentu yang tidak memiliki properti isi.<br/>            Hanya-baca [`IFillFormat`](/slides/python-net/id/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/id/aspose.slides/videoframe/hyperlink_click/) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse.<br/>            Baca/tulis [`IHyperlink`](/slides/python-net/id/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/id/aspose.slides/videoframe/hyperlink_mouse_over/) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk gerakan mouse.<br/>            Baca/tulis [`IHyperlink`](/slides/python-net/id/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/id/aspose.slides/videoframe/hyperlink_manager/) | Mengembalikan manajer hyperlink.<br/>            Hanya-baca [`IHyperlinkManager`](/slides/python-net/id/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/id/aspose.slides/videoframe/hidden/) | Menentukan apakah shape tersembunyi.<br/>            Baca/tulis **bool**. |
| [`z_order_position`](/slides/python-net/id/aspose.slides/videoframe/z_order_position/) | Mengembalikan posisi sebuah shape dalam urutan z.<br/>            Shapes[0] mengembalikan shape di belakang urutan z,<br/>            dan Shapes[Shapes.Count - 1] mengembalikan shape di depan urutan z.<br/>            Hanya-baca **int**. |
| [`connection_site_count`](/slides/python-net/id/aspose.slides/videoframe/connection_site_count/) | Mengembalikan jumlah situs koneksi pada shape.<br/>            Hanya-baca **int**. |
| [`rotation`](/slides/python-net/id/aspose.slides/videoframe/rotation/) | Mengembalikan atau mengatur jumlah derajat rotasi shape tertentu di sekitar sumbu z. Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam.<br/>            Baca/tulis **float**. |
| [`x`](/slides/python-net/id/aspose.slides/videoframe/x/) | Mendapat atau mengatur koordinat x sudut kiri-atas shape, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`y`](/slides/python-net/id/aspose.slides/videoframe/y/) | Mendapat atau mengatur koordinat y sudut kiri-atas shape, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`width`](/slides/python-net/id/aspose.slides/videoframe/width/) | Mendapat atau mengatur lebar shape, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`height`](/slides/python-net/id/aspose.slides/videoframe/height/) | Mendapat atau mengatur tinggi shape, diukur dalam poin.<br/>            Baca/tulis **float**. |
| [`black_white_mode`](/slides/python-net/id/aspose.slides/videoframe/black_white_mode/) | Properti menentukan cara shape akan ditampilkan dalam mode tampilan hitam-putih..<br/>            Baca/tulis [`BlackWhiteMode`](/slides/python-net/id/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/id/aspose.slides/videoframe/unique_id/) | Mengembalikan pengidentifikasi internal berskala presentasi yang dimaksudkan untuk penggunaan oleh add-in atau kode lain.<br/>            Karena nilai ini dapat ditetapkan ulang oleh pengguna atau secara programatik, tidak boleh diperlakukan<br/>            sebagai kunci unik yang tetap.<br/>            Hanya-baca **int**.<br/>            Lihat juga [`Shape.office_interop_shape_id`](/slides/python-net/id/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/id/aspose.slides/videoframe/office_interop_shape_id/) | Mengembalikan pengidentifikasi unik berskala slide yang tetap konstan selama masa hidup shape dan<br/>            memungkinkan PowerPoint atau kode interop merujuk shape secara andal dari mana saja dalam dokumen.<br/>            Hanya-baca **int**.<br/>            Lihat juga [`Shape.unique_id`](/slides/python-net/id/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/id/aspose.slides/videoframe/alternative_text/) | Mengembalikan atau mengatur teks alternatif yang terkait dengan sebuah shape.<br/>            Baca/tulis **str**. |
| [`alternative_text_title`](/slides/python-net/id/aspose.slides/videoframe/alternative_text_title/) | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan sebuah shape.<br/>            Baca/tulis **str**. |
| [`name`](/slides/python-net/id/aspose.slides/videoframe/name/) | Mengembalikan atau mengatur nama shape.<br/>            Harus tidak None. Gunakan nilai string kosong jika diperlukan.<br/>            Baca/tulis **str**. |
| [`is_decorative`](/slides/python-net/id/aspose.slides/videoframe/is_decorative/) | Mendapat atau mengatur opsi 'Mark as decorative'<br/>            Baca/tulis **bool**. |
| [`shape_lock`](/slides/python-net/id/aspose.slides/videoframe/shape_lock/) | Mengembalikan kunci shape.<br/>            Hanya-baca [`IPictureFrameLock`](/slides/python-net/id/aspose.slides/ipictureframelock). |
| [`is_grouped`](/slides/python-net/id/aspose.slides/videoframe/is_grouped/) | Menentukan apakah shape dikelompokkan.<br/>            Hanya-baca **bool**. |
| [`parent_group`](/slides/python-net/id/aspose.slides/videoframe/parent_group/) | Mengembalikan objek GroupShape induk jika shape dikelompokkan. Jika tidak, mengembalikan None.<br/>            Hanya-baca [`IGroupShape`](/slides/python-net/id/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/id/aspose.slides/videoframe/slide/) | Mengembalikan slide induk dari sebuah shape.<br/>            Hanya-baca [`IBaseSlide`](/slides/python-net/id/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/id/aspose.slides/videoframe/presentation/) | Mengembalikan presentasi induk dari sebuah slide.<br/>            Hanya-baca [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation). |
| [`shape_style`](/slides/python-net/id/aspose.slides/videoframe/shape_style/) | Mengembalikan objek style shape.<br/>            Hanya-baca [`IShapeStyle`](/slides/python-net/id/aspose.slides/ishapestyle). |
| [`shape_type`](/slides/python-net/id/aspose.slides/videoframe/shape_type/) | Mengembalikan atau mengatur tipe AutoShape untuk PictureFrame.<br/>            Semua item yang diizinkan dari set [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype), <br/>            kecuali semua jenis garis:<br/><br/><br/>    ShapeType.Line,<br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/>    ShapeType.CurvedConnector5.<br/><br/><br/>            Baca/tulis [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype). |
| [`adjustments`](/slides/python-net/id/aspose.slides/videoframe/adjustments/) | Mengembalikan koleksi nilai penyesuaian shape.<br/>            Hanya-baca [`IAdjustValueCollection`](/slides/python-net/id/aspose.slides/iadjustvaluecollection). |
| [`picture_frame_lock`](/slides/python-net/id/aspose.slides/videoframe/picture_frame_lock/) | Mengembalikan kunci shape.<br/>            Hanya-baca [`IPictureFrameLock`](/slides/python-net/id/aspose.slides/ipictureframelock). |
| [`picture_format`](/slides/python-net/id/aspose.slides/videoframe/picture_format/) | Mengembalikan objek PictureFillFormat untuk frame gambar.<br/>            Hanya-baca [`IPictureFillFormat`](/slides/python-net/id/aspose.slides/ipicturefillformat). |
| [`relative_scale_height`](/slides/python-net/id/aspose.slides/videoframe/relative_scale_height/) | Mengembalikan atau mengatur skala tinggi (relatif terhadap ukuran gambar asli) dari frame gambar. Nilai 1.0 sesuai dengan 100%.<br/>            Baca/tulis **float**. |
| [`relative_scale_width`](/slides/python-net/id/aspose.slides/videoframe/relative_scale_width/) | Mengembalikan atau mengatur skala lebar (relatif terhadap ukuran gambar asli) dari frame gambar. Nilai 1.0 sesuai dengan 100%.<br/>            Baca/tulis **float**. |
| [`is_cameo`](/slides/python-net/id/aspose.slides/videoframe/is_cameo/) | Menentukan apakah PictureFrame adalah objek Cameo atau tidak.<br/>            Hanya-baca **bool**. |
| [`rewind_video`](/slides/python-net/id/aspose.slides/videoframe/rewind_video/) | Menentukan apakah video secara otomatis diputar ulang ke awal<br/>            segera setelah film selesai diputar.<br/>            Baca/tulis **bool**. |
| [`play_loop_mode`](/slides/python-net/id/aspose.slides/videoframe/play_loop_mode/) | Menentukan apakah video diulang secara terus-menerus.<br/>            Baca/tulis **bool**. |
| [`hide_at_showing`](/slides/python-net/id/aspose.slides/videoframe/hide_at_showing/) | Menentukan apakah VideoFrame tersembunyi.<br/>            Baca/tulis **bool**. |
| [`volume`](/slides/python-net/id/aspose.slides/videoframe/volume/) | Mengembalikan atau mengatur volume audio.<br/>            Baca/tulis [`AudioVolumeMode`](/slides/python-net/id/aspose.slides/audiovolumemode). |
| [`play_mode`](/slides/python-net/id/aspose.slides/videoframe/play_mode/) | Mengembalikan atau mengatur mode pemutaran video.<br/>            Baca/tulis [`VideoPlayModePreset`](/slides/python-net/id/aspose.slides/videoplaymodepreset). |
| [`full_screen_mode`](/slides/python-net/id/aspose.slides/videoframe/full_screen_mode/) | Menentukan apakah video ditampilkan dalam mode layar penuh.<br/>            Baca/tulis **bool**. |
| [`link_path_long`](/slides/python-net/id/aspose.slides/videoframe/link_path_long/) | Mengembalikan atau mengatur nama file video yang ditautkan ke VideoFrame.<br/>            Baca/tulis **str**. |
| [`embedded_video`](/slides/python-net/id/aspose.slides/videoframe/embedded_video/) | Mengembalikan atau mengatur objek video yang disematkan.<br/>            Baca/tulis [`IVideo`](/slides/python-net/id/aspose.slides/ivideo). |
| [`trim_from_start`](/slides/python-net/id/aspose.slides/videoframe/trim_from_start/) | Pemotongan awal [ms] |
| [`trim_from_end`](/slides/python-net/id/aspose.slides/videoframe/trim_from_end/) | Pemotongan akhir [ms] |
| [`caption_tracks`](/slides/python-net/id/aspose.slides/videoframe/caption_tracks/) | Mengembalikan koleksi caption tertutup yang terkait dengan frame video.<br/>             Properti ini hanya-baca dan mengembalikan sebuah [`ICaptionsCollection`](/slides/python-net/id/aspose.slides/icaptionscollection) yang berisi semua trek caption. |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`get_image(self)`](/slides/python-net/id/aspose.slides/videoframe/get_image/#) | Mengembalikan thumbnail shape.<br/>            Tipe batas thumbnail shape ShapeThumbnailBounds.Shape digunakan secara default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/id/aspose.slides/videoframe/get_image/#shapethumbnailbounds-float-float) | Mengembalikan thumbnail shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/id/aspose.slides/videoframe/write_as_svg/#iorawiobase) | Menyimpan konten Shape sebagai file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/id/aspose.slides/videoframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Menyimpan konten Shape sebagai file SVG. |
| [`remove_placeholder(self)`](/slides/python-net/id/aspose.slides/videoframe/remove_placeholder/#) | Mendefinisikan bahwa shape ini bukan placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/id/aspose.slides/videoframe/add_placeholder/#iplaceholder) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [`get_base_placeholder(self)`](/slides/python-net/id/aspose.slides/videoframe/get_base_placeholder/#) | Mengembalikan shape placeholder dasar (shape dari tata letak dan/atau master slide yang diwarisi oleh shape saat ini).<br/>            None dikembalikan jika shape saat ini tidak diwarisi. |
| [`get_visual_bounds(self)`](/slides/python-net/id/aspose.slides/videoframe/get_visual_bounds/#) | Mendapat batas visual shape yang dihitung dari konten yang dirender. |
| [`get_geometry_paths(self)`](/slides/python-net/id/aspose.slides/videoframe/get_geometry_paths/#) | Mengembalikan salinan path shape geometri. Koordinat relatif terhadap sudut kiri atas shape. |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/id/aspose.slides/videoframe/set_geometry_path/#igeometrypath) | Memperbarui geometri shape dari objek [`IGeometryPath`](/slides/python-net/id/aspose.slides/igeometrypath). Koordinat harus relatif terhadap sudut kiri<br/>             atas shape.<br/>             Mengubah tipe shape ([`GeometryShape.shape_type`](/slides/python-net/id/aspose.slides/geometryshape/shape_type)) menjadi [`ShapeType.CUSTOM`](/slides/python-net/id/aspose.slides/shapetype/CUSTOM). |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/id/aspose.slides/videoframe/set_geometry_paths/#listigeometrypath) | Memperbarui geometri shape dari array [`IGeometryPath`](/slides/python-net/id/aspose.slides/igeometrypath). Koordinat harus relatif terhadap sudut kiri<br/>             atas shape.<br/>             Mengubah tipe shape ([`GeometryShape.shape_type`](/slides/python-net/id/aspose.slides/geometryshape/shape_type)) menjadi [`ShapeType.CUSTOM`](/slides/python-net/id/aspose.slides/shapetype/CUSTOM). |
| [`create_shape_elements(self)`](/slides/python-net/id/aspose.slides/videoframe/create_shape_elements/#) | Membuat dan mengembalikan array elemen shape. |

### Lihat Juga
* kelas [`GeometryShape`](/slides/python-net/id/aspose.slides/geometryshape)
* kelas [`PictureFrame`](/slides/python-net/id/aspose.slides/pictureframe)
* kelas [`Shape`](/slides/python-net/id/aspose.slides/shape)
* kelas [`VideoFrame`](/slides/python-net/id/aspose.slides/videoframe)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)