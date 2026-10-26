---
title: ILinkEmbedController class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.export/ilinkembedcontroller/
---
## ILinkEmbedController kelas

Antarmuka callback yang digunakan untuk menentukan bagaimana objek harus diproses selama penyimpanan.

Tipe ILinkEmbedController menampilkan anggota-anggota berikut:

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension)`](/slides/python-net/id/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/#int-bytes-str-str-str) | Menentukan dimana objek harus disimpan.<br/>            Metode ini dipanggil sekali untuk setiap id objek.<br/>            Tidak dijamin tidak akan ada dua objek dengan data, semanticName, dan contentType yang sama tetapi dengan id yang berbeda. |
| [`get_url(self, id, referrer)`](/slides/python-net/id/aspose.slides.export/ilinkembedcontroller/get_url/#int-int) | Mengembalikan URL ke objek eksternal.<br/>            Metode ini selalu dipanggil jika **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** mengembalikan [`LinkEmbedDecision.LINK`](/slides/python-net/id/aspose.slides.export/linkembeddecision/LINK) dan dapat dipanggil jika **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** mengembalikan [`LinkEmbedDecision.EMBED`](/slides/python-net/id/aspose.slides.export/linkembeddecision/EMBED) tetapi embedding tidak memungkinkan.<br/>            Dapat dipanggil berulang kali untuk id objek yang sama. |
| [`save_external(self, id, entity_data)`](/slides/python-net/id/aspose.slides.export/ilinkembedcontroller/save_external/#int-bytes) | Menyimpan objek eksternal. |

### Lihat Juga
* modul [`aspose.slides.export`](/slides/python-net/id/aspose.slides.export)
* perpustakaan [`Aspose.Slides`](/slides/python-net)