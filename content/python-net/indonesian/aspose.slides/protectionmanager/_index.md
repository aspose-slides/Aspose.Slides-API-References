---
title: ProtectionManager class
second_title: Referensi API Aspose.Slides untuk Python melalui .NET
description: 
type: docs
url: /id/aspose.slides/protectionmanager/
---
## ProtectionManager kelas

Manajemen perlindungan sandi presentasi.

Tipe ProtectionManager mengekspos anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/id/aspose.slides/protectionmanager/encrypt_document_properties/) | Properti ini masuk akal, jika presentasi dilindungi sandi.<br/>            Jika true maka properti dokumen dienkripsi dalam file presentasi.<br/>            Jika false maka properti dokumen bersifat publik sementara presentasi dienkripsi.<br/>            Read/write **bool**. |
| [`is_encrypted`](/slides/python-net/id/aspose.slides/protectionmanager/is_encrypted/) | Mendapatkan nilai yang menunjukkan apakah instance ini terenkripsi.<br/>            Read-only **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/id/aspose.slides/protectionmanager/is_only_document_properties_loaded/) | Properti ini masuk akal, jika file presentasi dilindungi sandi dan properti dokumen <br/>            file ini bersifat publik.<br/>            Nilai true berarti hanya properti dokumen yang dimuat dari file presentasi terenkripsi tanpa menggunakan sandi.<br/>            Nilai false berarti seluruh presentasi terenkripsi dimuat dengan menggunakan sandi yang benar, bukan hanya properti dokumen yang dimuat.<br/>            Jika presentasi tidak terenkripsi maka nilai properti selalu false.<br/>            Jika properti dokumen dari file terenkripsi tidak publik maka nilai properti selalu false.<br/>            Jika Presentation.EncryptDocumentProperties bernilai true maka nilai properti IsOnlyDocumentPropertiesLoaded selalu false.<br/>            Read-only **bool**. |
| [`is_write_protected`](/slides/python-net/id/aspose.slides/protectionmanager/is_write_protected/) | Mendapatkan nilai yang menunjukkan apakah presentasi ini dilindungi penulisan.<br/>            Read-only **bool**. |
| [`encryption_password`](/slides/python-net/id/aspose.slides/protectionmanager/encryption_password/) | Mendapatkan sandi yang digunakan untuk enkripsi presentasi.<br/>            Read-only **str**. |
| [`read_only_recommended`](/slides/python-net/id/aspose.slides/protectionmanager/read_only_recommended/) | Mendapatkan atau mengatur rekomendasi hanya-baca.<br/>            Read/write **bool**. |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/id/aspose.slides/protectionmanager/encrypt/#str) | Mengenkripsi Presentation dengan sandi yang ditentukan. |
| [`remove_encryption(self)`](/slides/python-net/id/aspose.slides/protectionmanager/remove_encryption/#) | Menghapus enkripsi. |
| [`set_write_protection(self, password)`](/slides/python-net/id/aspose.slides/protectionmanager/set_write_protection/#str) | Mengatur perlindungan penulisan untuk presentasi ini dengan sandi yang ditentukan. |
| [`remove_write_protection(self)`](/slides/python-net/id/aspose.slides/protectionmanager/remove_write_protection/#) | Menghapus perlindungan penulisan untuk presentasi ini. |
| [`check_write_protection(self, password)`](/slides/python-net/id/aspose.slides/protectionmanager/check_write_protection/#str) | Menentukan apakah sebuah presentasi dilindungi sandi untuk dimodifikasi. |

### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)