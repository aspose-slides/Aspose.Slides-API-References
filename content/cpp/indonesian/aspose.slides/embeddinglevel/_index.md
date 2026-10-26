---
title: EmbeddingLevel
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili hak lisensi untuk menyematkan font.
type: docs
weight: 5786
url: /id/aspose.slides/embeddinglevel/
---
## EmbeddingLevel enum

Mewakili hak lisensi untuk menyematkan font.

```cpp
enum class EmbeddingLevel : uint16_t
```

### Values

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Installable | 0 | [Fonts](../fonts/) dengan pengaturan ini menunjukkan bahwa mereka dapat disematkan dan dipasang secara permanen pada sistem remote oleh sebuah aplikasi. Pengguna sistem remote memperoleh hak, kewajiban, dan lisensi yang identik untuk font tersebut seperti pembeli asli font, dan tunduk pada perjanjian lisensi pengguna akhir, hak cipta, paten desain, dan/atau merek dagang yang sama seperti pembeli asli. |
| Restricted | 2 | [Fonts](../fonts/) yang hanya memiliki bit ini yang disetel tidak boleh dimodifikasi, disematkan, atau dipertukarkan dengan cara apapun tanpa terlebih dahulu mendapatkan izin dari pemilik sah. |
| PreviewPrint | 4 | Ketika bit ini disetel, font dapat disematkan, dan dimuat sementara pada sistem remote. Dokumen yang berisi font Preview & Print harus dibuka \"read-only;\" tidak ada penyuntingan yang dapat diterapkan pada dokumen. |
| Editable | 8 | Ketika bit ini disetel, font dapat disematkan tetapi hanya boleh diinstal secara sementara pada sistem lain. Berbeda dengan font Preview & Print, dokumen yang berisi font Editable dapat dibuka untuk dibaca, penyuntingan diizinkan, dan perubahan dapat disimpan. |
| NoSubsetting | 256 | Ketika bit ini disetel, font tidak boleh disubset sebelum disematkan. Pembatasan penyematan lain yang ditentukan dalam bit 0-3 dan 9 juga berlaku. |
| BitmapOnly | 512 | Ketika bit ini disetel, hanya bitmap yang terdapat dalam font yang dapat disematkan. Tidak ada data outline yang dapat disematkan. Jika tidak ada bitmap yang tersedia dalam font, maka font dianggap tidak dapat disematkan dan layanan penyematan akan gagal. |

## Lihat Juga

* Namespace [Aspose::Slides](../)
* Perpustakaan [Aspose.Slides](../../)