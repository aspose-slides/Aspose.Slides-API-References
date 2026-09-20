---
title: SlideCollection class
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides/slidecollection/
---
## SlideCollection kelas

Mewakili koleksi slide.

Tipe SlideCollection mengekspos anggota-anggota berikut:

Mendapatkan elemen pada indeks yang ditentukan.
            Baca-saja [`Slide`](/slides/python-net/id/aspose.slides/slide).

## Indexer

| Nama | Deskripsi |
| :- | :- |
| [`[index]`](/slides/python-net/id/aspose.slides/slidecollection/__getitem__/) |  |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/id/aspose.slides/slidecollection/add_clone/#islide) | Menambahkan salinan slide tertentu ke akhir koleksi. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/id/aspose.slides/slidecollection/add_clone/#islide-isection) | Menambahkan salinan slide tertentu ke akhir bagian yang ditentukan. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/id/aspose.slides/slidecollection/add_clone/#islide-ilayoutslide) | Menambahkan salinan slide tertentu ke akhir koleksi. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/id/aspose.slides/slidecollection/add_clone/#islide-imasterslide-bool) | Menambahkan salinan slide sumber tertentu ke akhir koleksi.<br/>            Layout yang sesuai akan dipilih secara otomatis dari master yang ditentukan <br/>            (layout yang sesuai adalah layout dengan Type atau Name yang sama dengan <br/>            layout slide sumber). Jika tidak ada layout yang sesuai maka<br/>            layout slide sumber akan dikloning (jika allowCloneMissingLayout <br/>            bernilai true) atau PptxEditException akan dilempar (jika allowCloneMissingLayout<br/>            bernilai false). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/id/aspose.slides/slidecollection/insert_clone/#int-islide) | Menyisipkan salinan slide tertentu ke posisi yang ditentukan dalam koleksi. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/id/aspose.slides/slidecollection/insert_clone/#int-islide-ilayoutslide) | Menyisipkan salinan slide tertentu ke posisi yang ditentukan dalam koleksi. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/id/aspose.slides/slidecollection/insert_clone/#int-islide-imasterslide-bool) | Menyisipkan salinan slide sumber tertentu ke posisi yang ditentukan dalam koleksi.<br/>            Layout yang sesuai akan dipilih secara otomatis dari master yang ditentukan <br/>            (layout yang sesuai adalah layout dengan Type atau Name yang sama dengan <br/>            layout slide sumber). Jika tidak ada layout yang sesuai maka<br/>            layout slide sumber akan dikloning (jika allowCloneMissingLayout <br/>            bernilai true) atau PptxEditException akan dilempar (jika allowCloneMissingLayout<br/>            bernilai false). |
| [`to_array(self)`](/slides/python-net/id/aspose.slides/slidecollection/to_array/#) | Membuat dan mengembalikan array yang berisi semua slide. |
| [`to_array(self, start_index, count)`](/slides/python-net/id/aspose.slides/slidecollection/to_array/#int-int) | Membuat dan mengembalikan array yang berisi semua slide dari rentang yang ditentukan.<br/>            Indeks slide pertama yang akan ditambahkan. Jumlah slide yang akan ditambahkan. |
| [`reorder(self, index, slide)`](/slides/python-net/id/aspose.slides/slidecollection/reorder/#int-islide) | Memindahkan slide dari koleksi ke posisi yang ditentukan. |
| [`reorder(self, index, slides)`](/slides/python-net/id/aspose.slides/slidecollection/reorder/#int-listislide) | Memindahkan slide dari koleksi ke posisi yang ditentukan.<br/>            Slide akan ditempatkan mulai dari indeks sesuai urutan mereka muncul dalam daftar. |
| [`add_from_pdf(self, path)`](/slides/python-net/id/aspose.slides/slidecollection/add_from_pdf/#str) | Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/id/aspose.slides/slidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi dengan mempertimbangkan opsi impor PDF. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/id/aspose.slides/slidecollection/add_from_pdf/#iorawiobase) | Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/id/aspose.slides/slidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/id/aspose.slides/slidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi. |
| [`add_from_html(self, html_text)`](/slides/python-net/id/aspose.slides/slidecollection/add_from_html/#str) | Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/id/aspose.slides/slidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi. |
| [`add_from_html(self, html_stream)`](/slides/python-net/id/aspose.slides/slidecollection/add_from_html/#iorawiobase) | Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/id/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/id/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/id/aspose.slides/slidecollection/insert_from_html/#int-str) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/id/aspose.slides/slidecollection/insert_from_html/#int-str-bool) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/id/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/id/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/id/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/id/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-bool) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [`add_empty_slide(self, layout)`](/slides/python-net/id/aspose.slides/slidecollection/add_empty_slide/#ilayoutslide) | Menambahkan slide kosong baru ke akhir koleksi. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/id/aspose.slides/slidecollection/insert_empty_slide/#int-ilayoutslide) | Menyisipkan salinan slide tertentu ke posisi yang ditentukan dalam koleksi. |
| [`remove(self, value)`](/slides/python-net/id/aspose.slides/slidecollection/remove/#islide) | Menghapus kemunculan pertama dari objek tertentu dalam koleksi. |
| [`remove_at(self, index)`](/slides/python-net/id/aspose.slides/slidecollection/remove_at/#int) | Menghapus elemen pada indeks yang ditentukan dalam koleksi. |
| [`index_of(self, slide)`](/slides/python-net/id/aspose.slides/slidecollection/index_of/#islide) | Mengembalikan indeks slide yang ditentukan dalam koleksi. |

### Lihat Juga
* kelas [`Slide`](/slides/python-net/id/aspose.slides/slide)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)