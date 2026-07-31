---
title: Overlaps()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah dua ReadOnlySpan tumpang tindih di memori tanpa menghitung offset.
type: docs
weight: 274
url: /id/system.memoryextensions/overlaps/
---
## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Menentukan apakah dua ReadOnlySpan saling tumpang tindih di memori tanpa menghitung offset.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span pertama yang diperiksa untuk tumpang tindih |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span kedua yang diperiksa untuk tumpang tindih |

### Nilai Kembalian

true jika span berbagi lokasi memori yang sama, false sebaliknya

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Menentukan apakah [Span](../../system/span/) dan [ReadOnlySpan](../../system/readonlyspan/) saling tumpang tindih di memori tanpa menghitung offset.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) yang diperiksa untuk tumpang tindih |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) yang diperiksa untuk tumpang tindih |

### Nilai Kembalian

true jika span berbagi lokasi memori yang sama, false sebaliknya

## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) function

Menentukan apakah dua ReadOnlySpan saling tumpang tindih di memori dan menghitung offset.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span pertama yang diperiksa untuk tumpang tindih |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span kedua yang diperiksa untuk tumpang tindih |
| elementOffset | **int32_t**\& | Parameter output yang menerima offset antara span jika mereka tumpang tindih |

### Nilai Kembalian

true jika span berbagi lokasi memori yang sama, false sebaliknya

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) function

Menentukan apakah [Span](../../system/span/) dan [ReadOnlySpan](../../system/readonlyspan/) saling tumpang tindih di memori dan menghitung offset.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) yang diperiksa untuk tumpang tindih |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) yang diperiksa untuk tumpang tindih |
| elementOffset | **int32_t**\& | Parameter output yang menerima offset antara span jika mereka tumpang tindih |

### Nilai Kembalian

true jika span berbagi lokasi memori yang sama, false sebaliknya

## Lihat Juga

* Kelas [ReadOnlySpan](../../system/readonlyspan/)
* Kelas [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Pustaka [Aspose.Slides](../../)