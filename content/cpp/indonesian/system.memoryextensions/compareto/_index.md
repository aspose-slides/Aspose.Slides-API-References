---
title: CompareTo()
second_title: Referensi API Aspose.Slides untuk C++
description: Membandingkan dua rentang karakter dengan aturan perbandingan string yang ditentukan.
type: docs
weight: 404
url: /id/system.memoryextensions/compareto/
---
## System::MemoryExtensions::CompareTo(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) fungsi


Membandingkan dua rentang karakter dengan aturan perbandingan string yang ditentukan.

```cpp
int32_t System::MemoryExtensions::CompareTo(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Rentang karakter pertama |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Rentang karakter kedua |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Jenis perbandingan string yang akan dilakukan |

### Nilai Kembalian

Nilai negatif jika span < other, nol jika sama, positif jika span > other

## Lihat Juga

* Enum [StringComparison](../../system/stringcomparison/)
* Kelas [ReadOnlySpan](../../system/readonlyspan/)
* Ruang Nama [System::MemoryExtensions](../)
* Perpustakaan [Aspose.Slides](../../)