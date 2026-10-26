---
title: LastIndexOf()
second_title: Referensi API Aspose.Slides untuk C++
description: Menemukan kemunculan terakhir dari sebuah urutan dalam span.
type: docs
weight: 209
url: /id/system.memoryextensions/lastindexof/
---
## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Menemukan kemunculan terakhir dari sebuah urutan dalam span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | The type of elements in the span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence to search for |

### Nilai Kembali

Indeks berbasis nol dari kemunculan terakhir, atau -1 jika tidak ditemukan

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const T\&) function

Menemukan kemunculan terakhir dari satu nilai dalam span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const T &value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | The type of elements in the span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value | const T\& | The value to search for |

### Nilai Kembali

Indeks berbasis nol dari kemunculan terakhir, atau -1 jika tidak ditemukan

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Menemukan kemunculan terakhir dari sebuah urutan dalam span yang dapat diubah.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | The type of elements in the span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence to search for |

### Nilai Kembali

Indeks berbasis nol dari kemunculan terakhir, atau -1 jika tidak ditemukan

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const T\&) function

Menemukan kemunculan terakhir dari satu nilai dalam span yang dapat diubah.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const T &value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | The type of elements in the span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value | const T\& | The value to search for |

### Nilai Kembali

Indeks berbasis nol dari kemunculan terakhir, atau -1 jika tidak ditemukan

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function

Menemukan kemunculan terakhir dari sebuah nilai dalam span menggunakan perbandingan string yang ditentukan.

```cpp
int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The span to search within |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The value to search for |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Jenis perbandingan string yang akan dilakukan |

### Nilai Kembali

Indeks berbasis nol dari kemunculan terakhir, atau -1 jika tidak ditemukan

## Lihat Juga

* Enum [StringComparison](../../system/stringcomparison/)
* Kelas [ReadOnlySpan](../../system/readonlyspan/)
* Kelas [Span](../../system/span/)
* Ruang Nama [System::MemoryExtensions](../)
* Pustaka [Aspose.Slides](../../)