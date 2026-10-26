---
title: ToUpper()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengubah karakter menjadi huruf kapital menggunakan kultur yang ditentukan.
type: docs
weight: 469
url: /id/system.memoryextensions/toupper/
---
## System::MemoryExtensions::ToUpper(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) fungsi

Mengubah karakter menjadi huruf kapital menggunakan kultur yang ditentukan.

```cpp
int32_t System::MemoryExtensions::ToUpper(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Rentang karakter sumber untuk dikonversi |
| destination | [Span](../../system/span/)\<char16_t\>\& | Rentang tujuan untuk menyimpan karakter yang telah dikonversi |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | Kultur yang digunakan untuk konversi (nullptr untuk kultur saat ini) |

### Nilai Kembali

Jumlah karakter yang dikonversi, atau -1 jika tujuan terlalu kecil

## Lihat Juga

* Typedef [SharedPtr](../../system/sharedptr/)
* Kelas [ReadOnlySpan](../../system/readonlyspan/)
* Kelas [Span](../../system/span/)
* Kelas [CultureInfo](../../system.globalization/cultureinfo/)
* Ruang Nama [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)