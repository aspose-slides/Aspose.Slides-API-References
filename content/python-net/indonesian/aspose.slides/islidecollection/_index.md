---
title: ISlideCollection class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/islidecollection/
---
## ISlideCollection kelas

Mewakili kumpulan slide.

Tipe ISlideCollection mengekspos anggota-anggota berikut:

Mendapatkan elemen pada indeks yang ditentukan.  
Hanya-baca [`ISlide`](/slides/python-net/id/aspose.slides/islide).

## Pengindeks

| Nama | Deskripsi |
| :- | :- |
| [`[index]`](/slides/python-net/id/aspose.slides/islidecollection/__getitem__/) |  |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/id/aspose.slides/islidecollection/add_clone/#islide) | Menambahkan salinan slide yang ditentukan ke akhir koleksi. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/id/aspose.slides/islidecollection/add_clone/#islide-isection) | Menambahkan salinan slide yang ditentukan ke akhir bagian yang ditentukan. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/id/aspose.slides/islidecollection/add_clone/#islide-ilayoutslide) | Menambahkan salinan slide yang ditentukan ke akhir koleksi. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/id/aspose.slides/islidecollection/add_clone/#islide-imasterslide-bool) | Menambahkan salinan slide sumber yang ditentukan ke akhir koleksi.<br/>            Tata letak yang sesuai akan dipilih secara otomatis dari master yang ditentukan <br/>            (tata letak yang sesuai adalah tata letak dengan Type atau Name yang sama dengan <br/>            tata letak slide sumber). Jika tidak ada tata letak yang sesuai maka<br/>            tata letak slide sumber akan digandakan (jika allowCloneMissingLayout <br/>            bernilai true) atau PptxEditException akan dilempar (jika allowCloneMissingLayout<br/>            bernilai false). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/id/aspose.slides/islidecollection/insert_clone/#int-islide) | Menyisipkan salinan slide yang ditentukan ke posisi yang ditentukan dalam koleksi. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/id/aspose.slides/islidecollection/insert_clone/#int-islide-ilayoutslide) | Menyisipkan salinan slide yang ditentukan ke posisi yang ditentukan dalam koleksi. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/id/aspose.slides/islidecollection/insert_clone/#int-islide-imasterslide-bool) | Menyisipkan salinan slide sumber yang ditentukan ke posisi yang ditentukan dalam koleksi.<br/>            Tata letak yang sesuai akan dipilih secara otomatis dari master yang ditentukan <br/>            (tata letak yang sesuai adalah tata letak dengan Type atau Name yang sama dengan <br/>            tata letak slide sumber). Jika tidak ada tata letak yang sesuai maka<br/>            tata letak slide sumber akan digandakan (jika allowCloneMissingLayout <br/>            bernilai true) atau PptxEditException akan dilempar (jika allowCloneMissingLayout<br/>            bernilai false). |
| [`to_array(self)`](/slides/python-net/id/aspose.slides/islidecollection/to_array/#) | Membuat dan mengembalikan array dengan semua slide di dalamnya. |
| [`to_array(self, start_index, count)`](/slides/python-net/id/aspose.slides/islidecollection/to_array/#int-int) | Membuat dan mengembalikan array dengan semua slide dari rentang yang ditentukan di dalamnya. |
| [`reorder(self, index, slide)`](/slides/python-net/id/aspose.slides/islidecollection/reorder/#int-islide) | Memindahkan slide dari koleksi ke posisi yang ditentukan. |
| [`reorder(self, index, slides)`](/slides/python-net/id/aspose.slides/islidecollection/reorder/#int-listislide) | Memindahkan slide dari koleksi ke posisi yang ditentukan.<br/>            Slide akan ditempatkan mulai dari indeks sesuai urutan mereka muncul dalam daftar. |
| [`add_from_pdf(self, path)`](/slides/python-net/id/aspose.slides/islidecollection/add_from_pdf/#str) | Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/id/aspose.slides/islidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi dengan mempertimbangkan opsi impor pdf. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/id/aspose.slides/islidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/id/aspose.slides/islidecollection/add_from_pdf/#iorawiobase) | Membuat slide dari dokumen PDF dan menambahkannya ke akhir koleksi. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/id/aspose.slides/islidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi. |
| [`add_from_html(self, html_text)`](/slides/python-net/id/aspose.slides/islidecollection/add_from_html/#str) | Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/id/aspose.slides/islidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi. |
| [`add_from_html(self, html_stream)`](/slides/python-net/id/aspose.slides/islidecollection/add_from_html/#iorawiobase) | Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/id/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/id/aspose.slides/islidecollection/insert_from_html/#int-str) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/id/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/id/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/id/aspose.slides/islidecollection/insert_from_html/#int-str-bool) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/id/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/id/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-bool) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/id/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan. |
| [`add_empty_slide(self, layout)`](/slides/python-net/id/aspose.slides/islidecollection/add_empty_slide/#ilayoutslide) | Menambahkan slide kosong baru ke akhir koleksi. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/id/aspose.slides/islidecollection/insert_empty_slide/#int-ilayoutslide) | Menyisipkan salinan slide yang ditentukan ke posisi yang ditentukan dalam koleksi. |
| [`remove(self, value)`](/slides/python-net/id/aspose.slides/islidecollection/remove/#islide) | Menghapus kemunculan pertama dari objek tertentu dalam koleksi. |
| [`remove_at(self, index)`](/slides/python-net/id/aspose.slides/islidecollection/remove_at/#int) | Menghapus elemen pada indeks yang ditentukan dalam koleksi. |
| [`index_of(self, slide)`](/slides/python-net/id/aspose.slides/islidecollection/index_of/#islide) | Mengembalikan indeks slide yang ditentukan dalam koleksi. |


### Lihat Juga
* kelas [`ISlide`](/slides/python-net/id/aspose.slides/islide)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)