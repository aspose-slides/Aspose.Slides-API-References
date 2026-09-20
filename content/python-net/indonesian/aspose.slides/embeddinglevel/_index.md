---
title: EmbeddingLevel enumeration
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides/embeddinglevel/
---
## enumerasi EmbeddingLevel

Mewakili hak lisensi untuk menyematkan font.

Tipe EmbeddingLevel menampilkan anggota-anggota berikut:

## Bidang

| Bidang | Deskripsi |
| :- | :- |
| INSTALLABLE | Font dengan pengaturan ini menunjukkan bahwa mereka dapat disematkan dan dipasang secara permanen pada sistem remote oleh sebuah aplikasi. <br/>            Pengguna sistem remote memperoleh hak, kewajiban, dan lisensi yang identik untuk font tersebut seperti pembeli asli font, <br/>            dan tunduk pada perjanjian lisensi pengguna akhir, hak cipta, paten desain, dan/atau merek dagang yang sama seperti pembeli asli. |
| RESTRICTED | Font yang hanya memiliki bit ini yang diaktifkan tidak boleh dimodifikasi, disematkan, atau ditukar dengan cara apa pun tanpa terlebih dahulu memperoleh izin dari pemilik sah. |
| PREVIEW_PRINT | Ketika bit ini diaktifkan, font dapat disematkan, dan dimuat sementara pada sistem remote. Dokumen yang berisi font Preview & <br/>            Print harus dibuka "read-only;" tidak ada pengeditan yang dapat diterapkan pada dokumen. |
| EDITABLE | Ketika bit ini diaktifkan, font dapat disematkan tetapi hanya boleh dipasang sementara pada sistem lain. Berbeda dengan font Preview & <br/>            Print, dokumen yang berisi font Editable dapat dibuka untuk dibaca, pengeditan diizinkan, dan perubahan dapat disimpan. |
| NO_SUBSETTING | Ketika bit ini diaktifkan, font tidak boleh disubset sebelum disematkan. Pembatasan penyematan lain yang ditentukan dalam bit 0-3 dan 9 juga berlaku. |
| BITMAP_ONLY | Ketika bit ini diaktifkan, hanya bitmap yang terdapat dalam font yang dapat disematkan. Tidak ada data outline yang dapat disematkan. Jika tidak ada bitmap yang tersedia dalam font, <br/>            maka font dianggap tidak dapat disematkan dan layanan penyematan akan gagal. |


### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)