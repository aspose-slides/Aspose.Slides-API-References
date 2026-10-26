---
title: ToLower()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengubah karakter menjadi huruf kecil menggunakan budaya yang ditentukan.
type: docs
weight: 443
url: /id/system.memoryextensions/tolower/
---
## System::MemoryExtensions::ToLower(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) fungsi

Mengubah karakter menjadi huruf kecil menggunakan budaya yang ditentukan.

```cpp
int32_t System::MemoryExtensions::ToLower(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Rentang karakter sumber untuk diubah |
| destination | [Span](../../system/span/)\<char16_t\>\& | Rentang tujuan untuk menyimpan karakter yang diubah |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | Budaya yang digunakan untuk konversi (nullptr untuk budaya saat ini) |

### Nilai Kembali

Jumlah karakter yang diubah, atau -1 jika tujuan terlalu kecil

## Lihat Juga

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Class [CultureInfo](../../system.globalization/cultureinfo/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)