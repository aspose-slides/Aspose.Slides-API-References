---
title: Chart class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/chart/
---
## Kelas Chart

Represents an graphic chart on a slide.

**Inheritance:**[`Chart`](/slides/python-net/id/aspose.slides.charts/chart) → [`GraphicalObject`](/slides/python-net/id/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/id/aspose.slides/shape)

The Chart type exposes the following members:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`is_text_holder`](/slides/python-net/id/aspose.slides.charts/chart/is_text_holder/) | Menentukan apakah shape adalah TextHolder_PPT.<br/>            Baca-saja **bool**. |
| [`placeholder`](/slides/python-net/id/aspose.slides.charts/chart/placeholder/) | Mengembalikan placeholder untuk sebuah shape. Mengembalikan None jika shape tidak memiliki placeholder.<br/>            Baca-saja [`IPlaceholder`](/slides/python-net/id/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/id/aspose.slides.charts/chart/custom_data/) | Mengembalikan data khusus shape.<br/>            Baca-saja [`ICustomData`](/slides/python-net/id/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/id/aspose.slides.charts/chart/raw_frame/) | Mengembalikan atau mengatur properti frame shape mentah.<br/>            Baca/tulis [`IShapeFrame`](/slides/python-net/id/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/id/aspose.slides.charts/chart/frame/) | Mengembalikan atau mengatur properti frame shape.<br/>            Baca/tulis [`IShapeFrame`](/slides/python-net/id/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/id/aspose.slides.charts/chart/line_format/) | Mengembalikan objek LineFormat yang berisi properti pemformatan garis untuk sebuah shape.<br/>            Catatan: dapat mengembalikan None untuk tipe shape tertentu yang tidak memiliki properti garis.<br/>            Baca-saja [`ILineFormat`](/slides/python-net/id/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/id/aspose.slides.charts/chart/three_d_format/) | Mengembalikan objek ThreeDFormat yang berisi properti efek 3d untuk sebuah shape.<br/>            Catatan: dapat mengembalikan None untuk tipe shape tertentu yang tidak memiliki properti 3d.<br/>            Baca-saja [`IThreeDFormat`](/slides/python-net/id/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/id/aspose.slides.charts/chart/effect_format/) | Mengembalikan objek EffectFormat yang berisi efek piksel yang diterapkan pada sebuah shape.<br/>            Catatan: dapat mengembalikan None untuk tipe shape tertentu yang tidak memiliki properti efek.<br/>            Baca-saja [`IEffectFormat`](/slides/python-net/id/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/id/aspose.slides.charts/chart/fill_format/) | Mengembalikan objek FillFormat yang berisi properti pemformatan isi untuk sebuah shape.<br/>            Catatan: dapat mengembalikan None untuk tipe shape tertentu yang tidak memiliki properti isi.<br/>            Baca-saja [`IFillFormat`](/slides/python-net/id/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/id/aspose.slides.charts/chart/hyperlink_click/) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk klik mouse.<br/>            Baca/tulis [`IHyperlink`](/slides/python-net/id/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/id/aspose.slides.charts/chart/hyperlink_mouse_over/) | Mengembalikan atau mengatur hyperlink yang didefinisikan untuk mouse over.<br/>            Baca/tulis [`IHyperlink`](/slides/python-net/id/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/id/aspose.slides.charts/chart/hyperlink_manager/) | Mengembalikan manajer hyperlink.<br/>            Baca-saja [`IHyperlinkManager`](/slides/python-net/id/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/id/aspose.slides.charts/chart/hidden/) | Menentukan apakah shape disembunyikan.<br/>            Baca/tulis **bool**. |
| [`z_order_position`](/slides/python-net/id/aspose.slides.charts/chart/z_order_position/) | Mengembalikan posisi sebuah shape dalam urutan z.<br/>            Shapes[0] mengembalikan shape di belakang urutan z,<br/>            dan Shapes[Shapes.Count - 1] mengembalikan shape di depan urutan z.<br/>            Baca-saja **int**. |
| [`connection_site_count`](/slides/python-net/id/aspose.slides.charts/chart/connection_site_count/) | Mengembalikan jumlah situs koneksi pada shape.<br/>            Baca-saja **int**. |
| [`rotation`](/slides/python-net/id/aspose.slides.charts/chart/rotation/) | Mengembalikan atau mengatur jumlah derajat rotasi shape yang ditentukan sekitar sumbu z.<br/>            Nilai positif menunjukkan rotasi searah jarum jam; nilai negatif menunjukkan rotasi berlawanan arah jarum jam.<br/>            Baca/tulis **float**. |
| [`x`](/slides/python-net/id/aspose.slides.charts/chart/x/) | Mengambil atau mengatur koordinat x sudut kiri atas shape, diukur dalam point.<br/>            Baca/tulis **float**. |
| [`y`](/slides/python-net/id/aspose.slides.charts/chart/y/) | Mengambil atau mengatur koordinat y sudut kiri atas shape, diukur dalam point.<br/>            Baca/tulis **float**. |
| [`width`](/slides/python-net/id/aspose.slides.charts/chart/width/) | Mengambil atau mengatur lebar shape, diukur dalam point.<br/>            Baca/tulis **float**. |
| [`height`](/slides/python-net/id/aspose.slides.charts/chart/height/) | Mengambil atau mengatur tinggi shape, diukur dalam point.<br/>            Baca/tulis **float**. |
| [`black_white_mode`](/slides/python-net/id/aspose.slides.charts/chart/black_white_mode/) | Properti menentukan bagaimana shape akan dirender dalam mode tampilan hitam-putih..<br/>            Baca/tulis [`BlackWhiteMode`](/slides/python-net/id/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/id/aspose.slides.charts/chart/unique_id/) | Mengembalikan pengidentifikasi internal yang berskala presentasi yang dimaksudkan untuk digunakan oleh add-in atau kode lain.<br/>            Karena nilai ini dapat ditetapkan ulang oleh pengguna atau secara programatik, nilai ini tidak boleh diperlakukan<br/>            sebagai kunci unik yang persisten.<br/>            Baca-saja **int**.<br/>            Lihat juga [`Shape.office_interop_shape_id`](/slides/python-net/id/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/id/aspose.slides.charts/chart/office_interop_shape_id/) | Mengembalikan pengidentifikasi unik berskala slide yang tetap konstan selama masa hidup shape dan<br/>            memungkinkan PowerPoint atau kode interop merujuk shape secara handal dari mana saja dalam dokumen.<br/>            Baca-saja **int**.<br/>            Lihat juga [`Shape.unique_id`](/slides/python-net/id/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/id/aspose.slides.charts/chart/alternative_text/) | Mengembalikan atau mengatur teks alternatif yang terkait dengan shape.<br/>            Baca/tulis **str**. |
| [`alternative_text_title`](/slides/python-net/id/aspose.slides.charts/chart/alternative_text_title/) | Mengembalikan atau mengatur judul teks alternatif yang terkait dengan shape.<br/>            Baca/tulis **str**. |
| [`name`](/slides/python-net/id/aspose.slides.charts/chart/name/) | Mengembalikan atau mengatur nama shape.<br/>            Harus tidak None. Gunakan nilai string kosong jika diperlukan.<br/>            Baca/tulis **str**. |
| [`is_decorative`](/slides/python-net/id/aspose.slides.charts/chart/is_decorative/) | Mengambil atau mengatur opsi 'Tandai sebagai dekoratif'<br/>            Baca/tulis **bool**. |
| [`shape_lock`](/slides/python-net/id/aspose.slides.charts/chart/shape_lock/) | Mengembalikan kunci shape.<br/>            Baca-saja [`IGraphicalObjectLock`](/slides/python-net/id/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/id/aspose.slides.charts/chart/is_grouped/) | Menentukan apakah shape dikelompokkan.<br/>            Baca-saja **bool**. |
| [`parent_group`](/slides/python-net/id/aspose.slides.charts/chart/parent_group/) | Mengembalikan objek GroupShape induk jika shape dikelompokkan. Jika tidak, mengembalikan None.<br/>            Baca-saja [`IGroupShape`](/slides/python-net/id/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/id/aspose.slides.charts/chart/slide/) | Mengembalikan slide induk dari shape.<br/>            Baca-saja [`IBaseSlide`](/slides/python-net/id/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/id/aspose.slides.charts/chart/presentation/) | Mengembalikan presentasi induk dari slide.<br/>            Baca-saja [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/id/aspose.slides.charts/chart/graphical_object_lock/) | Mengembalikan kunci shape.<br/>            Baca-saja [`IGraphicalObjectLock`](/slides/python-net/id/aspose.slides/igraphicalobjectlock). |
| [`plot_visible_cells_only`](/slides/python-net/id/aspose.slides.charts/chart/plot_visible_cells_only/) | Menentukan apakah hanya sel yang terlihat yang dipetakan. False untuk memetakan sel yang terlihat dan tersembunyi.<br/>            Baca/tulis **bool**. |
| [`display_blanks_as`](/slides/python-net/id/aspose.slides.charts/chart/display_blanks_as/) | Mengembalikan atau mengatur cara memetakan sel kosong pada chart.<br/>            Baca/tulis [`DisplayBlanksAsType`](/slides/python-net/id/aspose.slides.charts/displayblanksastype). |
| [`chart_data`](/slides/python-net/id/aspose.slides.charts/chart/chart_data/) | Mengembalikan informasi tentang data tertaut atau tersemat yang terkait dengan chart.<br/>            Baca-saja [`IChartData`](/slides/python-net/id/aspose.slides.charts/ichartdata). |
| [`has_title`](/slides/python-net/id/aspose.slides.charts/chart/has_title/) | Menentukan apakah chart memiliki judul yang terlihat.<br/>            Baca/tulis **bool**. |
| [`chart_title`](/slides/python-net/id/aspose.slides.charts/chart/chart_title/) | Mengembalikan atau mengatur judul chart.<br/>            Baca-saja [`IChartTitle`](/slides/python-net/id/aspose.slides.charts/icharttitle). |
| [`has_data_table`](/slides/python-net/id/aspose.slides.charts/chart/has_data_table/) | Menentukan apakah chart memiliki tabel data.<br/>            Baca/tulis **bool**. |
| [`has_legend`](/slides/python-net/id/aspose.slides.charts/chart/has_legend/) | Menentukan apakah chart memiliki legenda.<br/>            Baca/tulis **bool**. |
| [`legend`](/slides/python-net/id/aspose.slides.charts/chart/legend/) | Mengembalikan atau mengatur legenda untuk chart.<br/>            Baca-saja [`ILegend`](/slides/python-net/id/aspose.slides.charts/ilegend). |
| [`chart_data_table`](/slides/python-net/id/aspose.slides.charts/chart/chart_data_table/) | Mengembalikan tabel data sebuah chart.<br/>            Baca-saja [`IDataTable`](/slides/python-net/id/aspose.slides.charts/idatatable). |
| [`style`](/slides/python-net/id/aspose.slides.charts/chart/style/) | Mengembalikan atau mengatur gaya chart.<br/>            Baca/tulis [`StyleType`](/slides/python-net/id/aspose.slides.charts/styletype). |
| [`type`](/slides/python-net/id/aspose.slides.charts/chart/type/) | Mengembalikan atau mengatur tipe chart.<br/>            Baca/tulis [`ChartType`](/slides/python-net/id/aspose.slides.charts/charttype). |
| [`plot_area`](/slides/python-net/id/aspose.slides.charts/chart/plot_area/) | Mewakili area plot sebuah chart.<br/>            Baca-saja [`IChartPlotArea`](/slides/python-net/id/aspose.slides.charts/ichartplotarea). |
| [`rotation_3d`](/slides/python-net/id/aspose.slides.charts/chart/rotation_3d/) | Mengembalikan rotasi 3D sebuah chart.<br/>            Baca-saja [`IRotation3D`](/slides/python-net/id/aspose.slides.charts/irotation3d). |
| [`back_wall`](/slides/python-net/id/aspose.slides.charts/chart/back_wall/) | Mengembalikan objek yang memungkinkan mengubah format dinding belakang chart 3D.<br/>            Baca-saja [`IChartWall`](/slides/python-net/id/aspose.slides.charts/ichartwall). |
| [`side_wall`](/slides/python-net/id/aspose.slides.charts/chart/side_wall/) | Mengembalikan objek yang memungkinkan mengubah format dinding samping chart 3D.<br/>            Baca-saja [`IChartWall`](/slides/python-net/id/aspose.slides.charts/ichartwall). |
| [`floor`](/slides/python-net/id/aspose.slides.charts/chart/floor/) | Mengembalikan objek yang memungkinkan mengubah format lantai chart 3D.<br/>            Baca-saja [`IChartWall`](/slides/python-net/id/aspose.slides.charts/ichartwall). |
| [`text_format`](/slides/python-net/id/aspose.slides.charts/chart/text_format/) | Mengembalikan format teks chart.<br/>            Properti tidak berlaku untuk tipe berikut: [`ChartType.TREEMAP`](/slides/python-net/id/aspose.slides.charts/charttype/TREEMAP), [`ChartType.SUNBURST`](/slides/python-net/id/aspose.slides.charts/charttype/SUNBURST),<br/>            [`ChartType.WATERFALL`](/slides/python-net/id/aspose.slides.charts/charttype/WATERFALL), [`ChartType.HISTOGRAM`](/slides/python-net/id/aspose.slides.charts/charttype/HISTOGRAM), [`ChartType.FUNNEL`](/slides/python-net/id/aspose.slides.charts/charttype/FUNNEL),[`ChartType.BOX_AND_WHISKER`](/slides/python-net/id/aspose.slides.charts/charttype/BOX_AND_WHISKER).<br/>            Baca-saja [`IChartTextFormat`](/slides/python-net/id/aspose.slides.charts/icharttextformat). |
| [`theme_manager`](/slides/python-net/id/aspose.slides.charts/chart/theme_manager/) | Mengembalikan manajer tema.<br/>            Baca-saja [`IOverrideThemeManager`](/slides/python-net/id/aspose.slides.theme/ioverridethememanager). |
| [`user_shapes`](/slides/python-net/id/aspose.slides.charts/chart/user_shapes/) | Menentukan shape yang digambar di atas chart.<br/>            Baca-saja [`IGroupShape`](/slides/python-net/id/aspose.slides/igroupshape). |
| [`axes`](/slides/python-net/id/aspose.slides.charts/chart/axes/) | Menyediakan akses ke sumbu chart.<br/>            Baca-saja [`IAxesManager`](/slides/python-net/id/aspose.slides.charts/iaxesmanager). |
| [`show_data_labels_over_maximum`](/slides/python-net/id/aspose.slides.charts/chart/show_data_labels_over_maximum/) | Menentukan label data di atas maksimum chart yang akan ditampilkan.<br/>            Baca/tulis **bool**. |
| [`has_rounded_corners`](/slides/python-net/id/aspose.slides.charts/chart/has_rounded_corners/) | Menentukan area chart akan memiliki sudut melengkung.<br/>            Baca/tulis **bool**. |
| [`chart`](/slides/python-net/id/aspose.slides.charts/chart/chart/) |  |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`get_image(self)`](/slides/python-net/id/aspose.slides.charts/chart/get_image/#) | Mengembalikan thumbnail shape.<br/>            Tipe batas thumbnail ShapeThumbnailBounds.Shape digunakan secara default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/id/aspose.slides.charts/chart/get_image/#shapethumbnailbounds-float-float) | Mengembalikan thumbnail shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/id/aspose.slides.charts/chart/write_as_svg/#iorawiobase) | Menyimpan konten Shape sebagai file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/id/aspose.slides.charts/chart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Menyimpan konten Shape sebagai file SVG. |
| [`remove_placeholder(self)`](/slides/python-net/id/aspose.slides.charts/chart/remove_placeholder/#) | Mendefinisikan bahwa shape ini bukan placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/id/aspose.slides.charts/chart/add_placeholder/#iplaceholder) | Menambahkan placeholder baru jika tidak ada dan mengatur properti placeholder ke yang ditentukan. |
| [`get_base_placeholder(self)`](/slides/python-net/id/aspose.slides.charts/chart/get_base_placeholder/#) | Mengembalikan shape placeholder dasar (shape dari tata letak dan/atau master slide yang diwarisi oleh shape saat ini).<br/>            None dikembalikan jika shape saat ini tidak diwarisi. |
| [`get_visual_bounds(self)`](/slides/python-net/id/aspose.slides.charts/chart/get_visual_bounds/#) | Mengambil batas visual shape yang dihitung dari kontennya yang dirender. |
| [`validate_chart_layout(self)`](/slides/python-net/id/aspose.slides.charts/chart/validate_chart_layout/#) | Menghitung nilai aktual elemen chart. Nilai aktual mencakup posisi elemen yang mengimplementasikan antarmuka IActualLayout <br/>            (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight)<br/>            dan nilai sumbu aktual (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, <br/>            IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |
| [`create_theme_effective(self)`](/slides/python-net/id/aspose.slides.charts/chart/create_theme_effective/#) | Mengembalikan tema efektif untuk chart ini. |

### Lihat Juga
* kelas [`Chart`](/slides/python-net/id/aspose.slides.charts/chart)
* kelas [`GraphicalObject`](/slides/python-net/id/aspose.slides/graphicalobject)
* kelas [`Shape`](/slides/python-net/id/aspose.slides/shape)
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)