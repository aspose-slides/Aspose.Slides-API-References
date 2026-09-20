---
title: IHtmlFormattingController class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.export/ihtmlformattingcontroller/
---
## IHtmlFormattingController kelas

Mengontrol pembuatan file html.

Tipe IHtmlFormattingController mengekspos anggota-anggota berikut:

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/id/aspose.slides.export/ihtmlformattingcontroller/write_document_start/#ihtmlgenerator-ipresentation) | Dipanggil untuk menulis header dokumen html. Dipanggil sekali per konversi presentasi. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/id/aspose.slides.export/ihtmlformattingcontroller/write_document_end/#ihtmlgenerator-ipresentation) | Dipanggil untuk menulis footer dokumen html. Dipanggil sekali per konversi presentasi. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/id/aspose.slides.export/ihtmlformattingcontroller/write_slide_start/#ihtmlgenerator-islide) | Dipanggil untuk menulis header slide html. Dipanggil sekali per setiap slide. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/id/aspose.slides.export/ihtmlformattingcontroller/write_slide_end/#ihtmlgenerator-islide) | Dipanggil untuk menulis footer slide html. Dipanggil sekali per setiap slide. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/id/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/#ihtmlgenerator-ishape) | Dipanggil sebelum rendering shape. Dipanggil sekali per setiap shape. Jika fungsi ini menulis apa pun ke generator, pembuatan gambar slide saat ini akan selesai, fragmen html yang ditambahkan akan disisipkan dan gambar baru akan dimulai di atas yang sebelumnya. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/id/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/#ihtmlgenerator-ishape) | Dipanggil sebelum rendering shape. Dipanggil sekali per setiap shape. Jika fungsi ini menulis apa pun ke generator, pembuatan gambar slide saat ini akan selesai, fragmen html yang ditambahkan akan disisipkan dan gambar baru akan dimulai di atas yang sebelumnya. |

### Lihat Juga
* modul [`aspose.slides.export`](/slides/python-net/id/aspose.slides.export)
* perpustakaan [`Aspose.Slides`](/slides/python-net)