---
title: Contains()
second_title: Referensi API Aspose.Slides untuk C++
description: Memeriksa apakah span hanya-baca berisi nilai tertentu.
type: docs
weight: 40
url: /id/system.memoryextensions/contains/
---
## System::MemoryExtensions::Contains(const ReadOnlySpan\<T\>\&, const T\&) fungsi

Memeriksa apakah span hanya-baca berisi nilai tertentu.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const ReadOnlySpan<T> &span, const T &value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span yang akan dicari |
| value | const T\& | Nilai yang dicari |

### Nilai Kembali

true jika nilai ditemukan dalam span, false jika tidak

## System::MemoryExtensions::Contains(const Span\<T\>\&, const T\&) fungsi

Memeriksa apakah span dapat diubah berisi nilai tertentu.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const Span<T> &span, const T &value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span yang dapat diubah untuk pencarian |
| value | const T\& | Nilai yang dicari |

### Nilai Kembali

true jika nilai ditemukan dalam span, false jika tidak

## System::MemoryExtensions::Contains(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) fungsi

Memeriksa apakah span karakter berisi span karakter lain dengan aturan perbandingan yang ditentukan.

```cpp
bool System::MemoryExtensions::Contains(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Span yang akan dicari |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Span yang dicari |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Tipe perbandingan string yang akan dilakukan |

### Nilai Kembali

true jika nilai ditemukan dalam span, false jika tidak

## Lihat Juga

* Enum [StringComparison](../../system/stringcomparison/)
* Kelas [ReadOnlySpan](../../system/readonlyspan/)
* Kelas [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)