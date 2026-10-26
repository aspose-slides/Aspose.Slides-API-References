---
title: EmbedAllFontsHtmlController class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.export/embedallfontshtmlcontroller/
---
## EmbedAllFontsHtmlController kelas

Kelas pengontrol pemformatan yang digunakan untuk menyematkan semua font presentasi dalam format WOFF.

Tipe EmbedAllFontsHtmlController menampilkan anggota-anggota berikut:

## Konstruktor

| Konstruktor | Deskripsi |
| :- | :- |
| [`__init__(self)`](/slides/python-net/id/aspose.slides.export/embedallfontshtmlcontroller/__init__/#) | Membuat instance baru |
| [`__init__(self, font_name_exclude_list)`](/slides/python-net/id/aspose.slides.export/embedallfontshtmlcontroller/__init__/#liststr) | Membuat instance baru |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/id/aspose.slides.export/embedallfontshtmlcontroller/write_document_start/#ihtmlgenerator-ipresentation) | Dipanggil untuk menulis header dokumen html. Dipanggil sekali per konversi presentasi. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/id/aspose.slides.export/embedallfontshtmlcontroller/write_document_end/#ihtmlgenerator-ipresentation) | Dipanggil untuk menulis footer dokumen html. Dipanggil sekali per konversi presentasi. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/id/aspose.slides.export/embedallfontshtmlcontroller/write_slide_start/#ihtmlgenerator-islide) | Dipanggil untuk menulis header slide html. Dipanggil sekali per setiap slide. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/id/aspose.slides.export/embedallfontshtmlcontroller/write_slide_end/#ihtmlgenerator-islide) | Dipanggil untuk menulis footer slide html. Dipanggil sekali per setiap slide. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/id/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/#ihtmlgenerator-ishape) | Dipanggil sebelum rendering shape. Dipanggil sekali per setiap shape. Jika fungsi ini menulis apa pun ke generator, pembuatan gambar slide saat ini akan selesai, fragmen html yang ditambahkan akan disisipkan dan gambar baru akan dimulai di atas yang sebelumnya. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/id/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/#ihtmlgenerator-ishape) | Dipanggil sebelum rendering shape. Dipanggil sekali per setiap shape. Jika fungsi ini menulis apa pun ke generator, pembuatan gambar slide saat ini akan selesai, fragmen html yang ditambahkan akan disisipkan dan gambar baru akan dimulai di atas yang sebelumnya. |
| [`write_all_fonts(self, generator, presentation)`](/slides/python-net/id/aspose.slides.export/embedallfontshtmlcontroller/write_all_fonts/#ihtmlgenerator-ipresentation) | Menulis semua font yang terdapat dalam [`Presentation`](/slides/python-net/id/aspose.slides/presentation). |
| [`write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data)`](/slides/python-net/id/aspose.slides.export/embedallfontshtmlcontroller/write_font/#ihtmlgenerator-ifontdata-ifontdata-str-str-bytes) | Menulis data sebagai base64 ke dalam dokumen HTML itu sendiri |


### Lihat Juga
* modul [`aspose.slides.export`](/slides/python-net/id/aspose.slides.export)
* pustaka [`Aspose.Slides`](/slides/python-net)