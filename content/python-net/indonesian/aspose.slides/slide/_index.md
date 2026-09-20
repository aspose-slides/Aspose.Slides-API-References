---
title: Slide class
second_title: Referensi API Aspose.Slides untuk Python melalui .NET
description: 
type: docs
url: /id/aspose.slides/slide/
---
## Kelas Slide

Mewakili slide dalam sebuah presentasi.

**Warisan:**[`Slide`](/slides/python-net/id/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/id/aspose.slides/baseslide)

Tipe Slide menampilkan anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`shapes`](/slides/python-net/id/aspose.slides/slide/shapes/) | Mengembalikan bentuk-bentuk slide.<br/>            Hanya-baca [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/id/aspose.slides/slide/controls/) | Mengembalikan koleksi kontrol ActiveX pada sebuah slide.<br/>            Hanya-baca [`IControlCollection`](/slides/python-net/id/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/id/aspose.slides/slide/name/) | Mengembalikan atau mengatur nama slide.<br/>            Baca/tulis **str**. |
| [`slide_id`](/slides/python-net/id/aspose.slides/slide/slide_id/) | Mengembalikan ID slide.<br/>            Hanya-baca **int**. |
| [`custom_data`](/slides/python-net/id/aspose.slides/slide/custom_data/) | Mengembalikan data khusus slide.<br/>            Hanya-baca [`ICustomData`](/slides/python-net/id/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/id/aspose.slides/slide/timeline/) | Mengembalikan objek timeline animasi.<br/>            Hanya-baca [`IAnimationTimeLine`](/slides/python-net/id/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/id/aspose.slides/slide/slide_show_transition/) | Mengembalikan objek Transition yang berisi informasi tentang<br/>            bagaimana slide yang ditentukan maju selama pertunjukan slide.<br/>            Hanya-baca [`ISlideShowTransition`](/slides/python-net/id/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/id/aspose.slides/slide/background/) | Mengembalikan latar belakang slide.<br/>            Hanya-baca [`IBackground`](/slides/python-net/id/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/id/aspose.slides/slide/hyperlink_queries/) | Menyediakan akses mudah ke hyperlink yang terkandung.<br/>            Hanya-baca [`IHyperlinkQueries`](/slides/python-net/id/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/id/aspose.slides/slide/show_master_shapes/) | Menentukan apakah bentuk pada master slide harus ditampilkan pada slide atau tidak.<br/>            Baca/tulis **bool**. |
| [`presentation`](/slides/python-net/id/aspose.slides/slide/presentation/) | Mengembalikan interface IPresentation.<br/>            Hanya-baca [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/id/aspose.slides/slide/header_footer_manager/) | Mengembalikan manajer HeaderFooter slide.<br/>            Hanya-baca [`ISlideHeaderFooterManager`](/slides/python-net/id/aspose.slides/islideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/id/aspose.slides/slide/theme_manager/) | Mengembalikan manajer tema yang menimpa.<br/>            Hanya-baca [`IOverrideThemeManager`](/slides/python-net/id/aspose.slides.theme/ioverridethememanager). |
| [`slide_number`](/slides/python-net/id/aspose.slides/slide/slide_number/) | Mengembalikan nomor slide.<br/>            Indeks slide dalam koleksi [`Presentation.slides`](/slides/python-net/id/aspose.slides/presentation/slides) selalu sama dengan SlideNumber - Presentation.FirstSlideNumber.<br/>            Baca/tulis **int**. |
| [`hidden`](/slides/python-net/id/aspose.slides/slide/hidden/) | Menentukan apakah slide yang ditentukan disembunyikan selama pertunjukan slide.<br/>            Baca/tulis **bool**. |
| [`layout_slide`](/slides/python-net/id/aspose.slides/slide/layout_slide/) | Mengembalikan atau mengatur layout slide untuk slide saat ini.<br/>            Baca/tulis [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/id/aspose.slides/slide/notes_slide_manager/) | Memungkinkan mengakses slide catatan, menambah dan menghapusnya.<br/>            Hanya-baca [`INotesSlideManager`](/slides/python-net/id/aspose.slides/inotesslidemanager). |
| [`slide`](/slides/python-net/id/aspose.slides/slide/slide/) |  |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/id/aspose.slides/slide/join_portions_with_same_formatting/#) | Menggabungkan run dengan pemformatan yang sama di semua paragraf dalam semua bentuk yang dapat diterima. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/id/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | Menggabungkan run dengan pemformatan yang sama di semua paragraf dalam semua bentuk yang dapat diterima. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/id/aspose.slides/slide/get_image/#float-float) | Mengembalikan objek Thumbnail Image dengan skala khusus. |
| [`get_image(self)`](/slides/python-net/id/aspose.slides/slide/get_image/#) | Mengembalikan objek Thumbnail Image (20% dari ukuran asli). |
| [`get_image(self, image_size)`](/slides/python-net/id/aspose.slides/slide/get_image/#asposepydrawingsize) | Mengembalikan objek Thumbnail Image dengan ukuran yang ditentukan. |
| [`get_image(self, options)`](/slides/python-net/id/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | Mengembalikan objek gambar tiff Thumbnail dengan parameter yang ditentukan. |
| [`get_image(self, options)`](/slides/python-net/id/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | Mengembalikan objek Thumbnail Image. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/id/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | Mengembalikan objek Thumbnail Image dengan skala khusus. |
| [`get_image(self, options, image_size)`](/slides/python-net/id/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Mengembalikan objek Thumbnail Image dengan ukuran yang ditentukan. |
| [`write_as_svg(self, stream)`](/slides/python-net/id/aspose.slides/slide/write_as_svg/#iorawiobase) | Menyimpan konten slide sebagai file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/id/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Menyimpan konten slide sebagai file SVG. |
| [`equals(self, slide)`](/slides/python-net/id/aspose.slides/slide/equals/#ibaseslide) | Menentukan apakah dua instance IBaseSlide sama.<br/>            Nilai yang dikembalikan dihitung berdasarkan struktur slide dan konten statis.<br/>            Dua slide dianggap sama jika semua bentuk, gaya, teks, animasi, dan pengaturan lainnya, dll., sama. Perbandingan tidak memperhitungkan nilai pengidentifikasi unik, misalnya SlideId, dan konten dinamis, misalnya nilai tanggal saat ini dalam Placeholder Tanggal. |
| [`create_theme_effective(self)`](/slides/python-net/id/aspose.slides/slide/create_theme_effective/#) | Mengembalikan tema efektif untuk slide ini. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/id/aspose.slides/slide/find_shape_by_alt_text/#str) | Menemukan kemunculan pertama sebuah bentuk dengan teks alternatif yang ditentukan. |
| [`write_as_emf(self, stream)`](/slides/python-net/id/aspose.slides/slide/write_as_emf/#iorawiobase) | Menyimpan konten slide sebagai file EMF. |
| [`remove(self)`](/slides/python-net/id/aspose.slides/slide/remove/#) | Menghapus slide dari presentasi. |
| [`reset(self)`](/slides/python-net/id/aspose.slides/slide/reset/#) | Mengatur ulang posisi, ukuran, dan format setiap bentuk yang memiliki prototipe pada LayoutSlide. |
| [`get_slide_comments(self, author)`](/slides/python-net/id/aspose.slides/slide/get_slide_comments/#icommentauthor) | Mengembalikan semua komentar slide yang ditambahkan oleh penulis tertentu. |


### Lihat Juga
* kelas [`BaseSlide`](/slides/python-net/id/aspose.slides/baseslide)
* kelas [`Slide`](/slides/python-net/id/aspose.slides/slide)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)