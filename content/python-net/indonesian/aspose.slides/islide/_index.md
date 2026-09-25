---
title: ISlide class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/islide/
---
## ISlide kelas

Mewakili sebuah slide dalam presentasi.

Tipe ISlide menampilkan anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/id/aspose.slides/islide/header_footer_manager/) | Mengembalikan manajer HeaderFooter dari slide.<br/>            Hanya-baca [`ISlideHeaderFooterManager`](/slides/python-net/id/aspose.slides/islideheaderfootermanager). |
| [`slide_number`](/slides/python-net/id/aspose.slides/islide/slide_number/) | Mengembalikan nomor slide.<br/>            Indeks slide dalam koleksi [`IPresentation.slides`](/slides/python-net/id/aspose.slides/ipresentation/slides) selalu sama dengan SlideNumber - 1.<br/>            Baca/tulis **int**. |
| [`hidden`](/slides/python-net/id/aspose.slides/islide/hidden/) | Menentukan apakah slide yang ditentukan disembunyikan selama pertunjukan slide.<br/>            Baca/tulis **bool**. |
| [`layout_slide`](/slides/python-net/id/aspose.slides/islide/layout_slide/) | Mengembalikan atau mengatur slide tata letak untuk slide saat ini.<br/>            Baca/tulis [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/id/aspose.slides/islide/notes_slide_manager/) | Mengizinkan akses ke slide catatan, menambah dan menghapusnya.<br/>            Hanya-baca [`INotesSlideManager`](/slides/python-net/id/aspose.slides/inotesslidemanager). |
| [`shapes`](/slides/python-net/id/aspose.slides/islide/shapes/) |  |
| [`controls`](/slides/python-net/id/aspose.slides/islide/controls/) |  |
| [`name`](/slides/python-net/id/aspose.slides/islide/name/) |  |
| [`slide_id`](/slides/python-net/id/aspose.slides/islide/slide_id/) |  |
| [`custom_data`](/slides/python-net/id/aspose.slides/islide/custom_data/) |  |
| [`timeline`](/slides/python-net/id/aspose.slides/islide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/id/aspose.slides/islide/slide_show_transition/) |  |
| [`background`](/slides/python-net/id/aspose.slides/islide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/id/aspose.slides/islide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/id/aspose.slides/islide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/id/aspose.slides/islide/slide/) |  |
| [`presentation`](/slides/python-net/id/aspose.slides/islide/presentation/) |  |
| [`theme_manager`](/slides/python-net/id/aspose.slides/islide/theme_manager/) |  |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/id/aspose.slides/islide/get_image/#float-float) | Mengembalikan objek gambar dengan skala khusus. |
| [`get_image(self)`](/slides/python-net/id/aspose.slides/islide/get_image/#) | Mengembalikan objek Gambar Thumbnail (20% ukuran asli). |
| [`get_image(self, image_size)`](/slides/python-net/id/aspose.slides/islide/get_image/#asposeslidessize) | Mengembalikan objek gambar dengan ukuran yang ditentukan. |
| [`get_image(self, options)`](/slides/python-net/id/aspose.slides/islide/get_image/#asposeslidesexportitiffoptions) | Mengembalikan objek bitmap tiff Thumbnail dengan parameter yang ditentukan. |
| [`get_image(self, options)`](/slides/python-net/id/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions) | Mengembalikan objek Bitmap Thumbnail. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/id/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-float-float) | Mengembalikan objek Bitmap Thumbnail dengan skala khusus. |
| [`get_image(self, options, image_size)`](/slides/python-net/id/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | Mengembalikan objek Bitmap Thumbnail dengan ukuran yang ditentukan. |
| [`write_as_svg(self, stream)`](/slides/python-net/id/aspose.slides/islide/write_as_svg/#iorawiobase) | Menyimpan konten slide sebagai file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/id/aspose.slides/islide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Menyimpan konten slide sebagai file SVG. |
| [`get_slide_comments(self, author)`](/slides/python-net/id/aspose.slides/islide/get_slide_comments/#icommentauthor) | Mengembalikan semua komentar slide yang ditambahkan oleh penulis tertentu. |
| [`write_as_emf(self, stream)`](/slides/python-net/id/aspose.slides/islide/write_as_emf/#iorawiobase) | Menyimpan konten slide sebagai file EMF. |
| [`remove(self)`](/slides/python-net/id/aspose.slides/islide/remove/#) | Menghapus slide dari presentasi. |
| [`reset(self)`](/slides/python-net/id/aspose.slides/islide/reset/#) | Mengatur ulang posisi, ukuran, dan pemformatan setiap bentuk yang memiliki prototipe pada LayoutSlide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/id/aspose.slides/islide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/id/aspose.slides/islide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/id/aspose.slides/islide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/id/aspose.slides/islide/create_theme_effective/#) |  |

### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)