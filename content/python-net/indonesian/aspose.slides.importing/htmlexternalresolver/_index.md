---
title: HtmlExternalResolver class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.importing/htmlexternalresolver/
---
## HtmlExternalResolver kelas

Objek callback yang digunakan oleh prosedur impor HTML untuk memperoleh objek yang direferensikan seperti gambar.  
Menggunakan resolver ini dapat menimbulkan kerentanan ketika file HTML yang disediakan klien membuat perangkat lunak server memperoleh file lokal atau jaringan. Gunakan dengan hati-hati. Disarankan untuk tidak menyebutkan HtmlExternalResolver sama sekali (hanya objek tersemat yang akan dibaca) atau membuat subclass yang memeriksa apakah uri yang ditentukan valid.

Tipe HtmlExternalResolver mengekspos anggota-anggota berikut:

## Konstruktor

| Konstruktor | Deskripsi |
| :- | :- |
| [`__init__(self)`](/slides/python-net/id/aspose.slides.importing/htmlexternalresolver/__init__/#) |  |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/id/aspose.slides.importing/htmlexternalresolver/resolve_uri/#str-str) | Resolves the absolute URI from the base and relative URIs. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/id/aspose.slides.importing/htmlexternalresolver/get_entity/#str) | Maps a URI to an object containing the actual resource. |

### Lihat Juga
* modul [`aspose.slides.importing`](/slides/python-net/id/aspose.slides.importing)
* perpustakaan [`Aspose.Slides`](/slides/python-net)