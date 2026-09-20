---
title: IProtectionManager class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/iprotectionmanager/
---
## IProtectionManager kelas

Manajemen proteksi sandi presentasi.

Tipe IProtectionManager menampilkan anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/id/aspose.slides/iprotectionmanager/encrypt_document_properties/) | Properti ini masuk akal, jika presentasi dilindungi kata sandi.<br/>Jika true maka properti dokumen dienkripsi dalam file presentasi.<br/>Jika false maka properti dokumen bersifat publik sementara presentasi dienkripsi.<br/>Baca/tulis **bool**. |
| [`is_encrypted`](/slides/python-net/id/aspose.slides/iprotectionmanager/is_encrypted/) | Mendapatkan nilai yang menunjukkan apakah instance ini terenkripsi.<br/>Baca-saja **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/id/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/) | Properti ini masuk akal, jika file presentasi dilindungi kata sandi dan properti dokumen <br/>file ini bersifat publik.<br/>Nilai true berarti hanya properti dokumen yang dimuat dari file presentasi terenkripsi tanpa penggunaan kata sandi.<br/>Nilai false berarti seluruh presentasi terenkripsi dimuat dengan penggunaan kata sandi yang tepat, bukan hanya properti dokumen yang dimuat.<br/>Jika presentasi tidak terenkripsi maka nilai properti selalu false.<br/>Jika properti dokumen dari file terenkripsi tidak publik maka nilai properti selalu false.<br/>Jika PresentationEx.EncryptDocumentProperties bernilai true maka nilai properti IsOnlyDocumentPropertiesLoaded selalu false.<br/>Baca-saja **bool**. |
| [`is_write_protected`](/slides/python-net/id/aspose.slides/iprotectionmanager/is_write_protected/) | Mendapatkan nilai yang menunjukkan apakah presentasi ini dilindungi penulisan.<br/>Baca-saja **bool**. |
| [`encryption_password`](/slides/python-net/id/aspose.slides/iprotectionmanager/encryption_password/) | Mengembalikan kata sandi enkripsi.<br/>Baca-saja **str**. |
| [`read_only_recommended`](/slides/python-net/id/aspose.slides/iprotectionmanager/read_only_recommended/) | Mendapatkan atau mengatur rekomendasi baca-saja.<br/>Baca/tulis **bool**. |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/id/aspose.slides/iprotectionmanager/encrypt/#str) | Mengenkripsi Presentasi dengan kata sandi yang ditentukan. |
| [`remove_encryption(self)`](/slides/python-net/id/aspose.slides/iprotectionmanager/remove_encryption/#) | Menghapus enkripsi. |
| [`set_write_protection(self, password)`](/slides/python-net/id/aspose.slides/iprotectionmanager/set_write_protection/#str) | Menetapkan perlindungan penulisan untuk presentasi ini dengan kata sandi yang ditentukan. |
| [`remove_write_protection(self)`](/slides/python-net/id/aspose.slides/iprotectionmanager/remove_write_protection/#) | Menghapus perlindungan penulisan untuk presentasi ini. |
| [`check_write_protection(self, password)`](/slides/python-net/id/aspose.slides/iprotectionmanager/check_write_protection/#str) | Menentukan apakah sebuah presentasi dilindungi kata sandi untuk dimodifikasi. |

### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)