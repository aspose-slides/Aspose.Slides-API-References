---
title: IPresentationInfo class
second_title: Referensi API Aspose.Slides untuk Python melalui .NET
description: 
type: docs
url: /id/aspose.slides/ipresentationinfo/
---
## IPresentationInfo kelas

Informasi tentang file presentasi

Tipe IPresentationInfo menampilkan anggota berikut:

## Properti

| Property | Description |
| :- | :- |
| [`is_encrypted`](/slides/python-net/id/aspose.slides/ipresentationinfo/is_encrypted/) | Mengembalikan True jika presentasi yang terikat dienkripsi, jika tidak False.<br/>Baca-saja **bool**. |
| [`is_password_protected`](/slides/python-net/id/aspose.slides/ipresentationinfo/is_password_protected/) | Mengembalikan nilai yang menunjukkan apakah presentasi yang terikat dilindungi dengan kata sandi untuk dibuka. |
| [`is_write_protected`](/slides/python-net/id/aspose.slides/ipresentationinfo/is_write_protected/) | Mengembalikan nilai yang menunjukkan apakah presentasi yang terikat dilindungi untuk ditulis. |
| [`load_format`](/slides/python-net/id/aspose.slides/ipresentationinfo/load_format/) | Mengembalikan format presentasi yang terikat.<br/>Baca-saja [`LoadFormat`](/slides/python-net/id/aspose.slides/loadformat). |

## Metode

| Method | Description |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/id/aspose.slides/ipresentationinfo/write_binded_presentation/#iorawiobase) | Menulis presentasi yang terikat ke aliran. |
| [`write_binded_presentation(self, file)`](/slides/python-net/id/aspose.slides/ipresentationinfo/write_binded_presentation/#str) | Menulis presentasi yang terikat ke file. |
| [`check_password(self, password)`](/slides/python-net/id/aspose.slides/ipresentationinfo/check_password/#str) | Memeriksa apakah kata sandi benar untuk presentasi yang dilindungi dengan kata sandi buka. |
| [`check_write_protection(self, password)`](/slides/python-net/id/aspose.slides/ipresentationinfo/check_write_protection/#str) | Memeriksa apakah kata sandi untuk mengubah benar untuk presentasi yang dilindungi penulisan. |
| [`read_document_properties(self)`](/slides/python-net/id/aspose.slides/ipresentationinfo/read_document_properties/#) | Mengembalikan properti dokumen dari presentasi yang terikat. |
| [`update_document_properties(self, document_properties)`](/slides/python-net/id/aspose.slides/ipresentationinfo/update_document_properties/#idocumentproperties) | Memperbarui properti presentasi yang terikat. |


### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)