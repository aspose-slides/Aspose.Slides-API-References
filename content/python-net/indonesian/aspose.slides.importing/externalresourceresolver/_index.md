---
title: ExternalResourceResolver class
second_title: Referensi API Aspose.Slides untuk Python melalui .NET
description: 
type: docs
url: /id/aspose.slides.importing/externalresourceresolver/
---
## ExternalResourceResolver kelas

Kelas callback digunakan untuk menyelesaikan sumber daya eksternal selama impor dokumen Html, Svg. Menggunakan resolver ini dapat menyebabkan kerentanan ketika file HTML atau SVG yang disediakan klien akan membuat perangkat lunak server memperoleh file lokal atau jaringan. Gunakan dengan hati-hati. Disarankan untuk tidak menyebutkan ExternalResourceResolver sama sekali (hanya objek tertanam yang akan dibaca) atau membuat subkelas tertentu yang memeriksa apakah uri yang ditentukan valid.

Tipe ExternalResourceResolver menampilkan anggota berikut:

## Konstruktor

| Konstruktor | Deskripsi |
| :- | :- |
| [`__init__(self)`](/slides/python-net/id/aspose.slides.importing/externalresourceresolver/__init__/#) |  |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/id/aspose.slides.importing/externalresourceresolver/resolve_uri/#str-str) | Menyelesaikan URI absolut dari URI dasar dan relatif. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/id/aspose.slides.importing/externalresourceresolver/get_entity/#str) | Memetakan URI ke objek yang berisi sumber daya aktual. |

### Lihat Juga
* modul [`aspose.slides.importing`](/slides/python-net/id/aspose.slides.importing)
* pustaka [`Aspose.Slides`](/slides/python-net)