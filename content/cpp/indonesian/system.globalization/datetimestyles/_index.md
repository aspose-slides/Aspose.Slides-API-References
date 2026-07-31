---
title: DateTimeStyles
second_title: Aspose.Slides untuk C++ Referensi API
description: Mendefinisikan opsi pemformatan tanggal dan waktu. Bit flag.
type: docs
weight: 456
url: /id/system.globalization/datetimestyles/
---
## DateTimeStyles enum

Mendefinisikan opsi pemformatan tanggal dan waktu. Bit flag.

```cpp
enum class DateTimeStyles : int32_t
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| None | 0 | Bawaan. |
| AllowLeadingWhite | 1 | Abaikan spasi putih di awal. |
| AllowTrailingWhite | 2 | Abaikan spasi putih di akhir. |
| AllowInnerWhite | 4 | Abaikan spasi putih di dalam. |
| AllowWhiteSpaces | n/a | Abaikan semua spasi putih. |
| NoCurrentDateDefault | 8 | Saat mem-parse string tanggal/waktu, jika semua tahun/bulan/hari tidak ada, tetapkan tanggal default ke 0001/1/1, bukan tahun/bulan/hari saat ini. |
| AdjustToUniversal | 16 | Saat mem-parse string tanggal/waktu, jika ada penentu zona waktu ("GMT","Z","+xxxx","-xxxx"), kami akan menyesuaikan waktu yang diparse ke GMT. |
| AssumeLocal | 32 | Jika tidak ada zona waktu yang diberikan, gunakan zona waktu lokal. |
| AssumeUniversal | 64 | Jika tidak ada zona waktu yang diberikan, gunakan UTC. |
| RoundtripKind | 128 | Coba pertahankan apakah masukan tidak ditentukan, lokal, atau UTC. |

## Lihat Juga

* Ruang Nama [System::Globalization](../)
* Perpustakaan [Aspose.Slides](../../)