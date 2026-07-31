---
title: StartsWith()
second_title: Referensi API Aspose.Slides untuk C++
description: Memeriksa apakah span dimulai dengan nilai yang ditentukan.
type: docs
weight: 352
url: /id/system.memoryextensions/startswith/
---
## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const T\&) fungsi

Memeriksa apakah span dimulai dengan nilai yang ditentukan.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const T &value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | The type of elements in the span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span yang akan diperiksa |
| value | const T\& | Nilai yang akan diperiksa di awal span |

### Nilai Kembali

true jika span dimulai dengan nilai, false bila tidak

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) fungsi

Memeriksa apakah span dimulai dengan span nilai yang ditentukan.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | The type of elements in the spans |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span yang akan diperiksa |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span yang berisi nilai untuk diperiksa di awal |

### Nilai Kembali

true jika span dimulai dengan span nilai, false bila tidak

## System::MemoryExtensions::StartsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) fungsi

Memeriksa apakah span yang dapat diubah dimulai dengan span nilai hanya-baca yang ditentukan.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | The type of elements in the spans |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span yang dapat diubah yang akan diperiksa |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span hanya-baca yang berisi nilai untuk diperiksa |

### Nilai Kembali

true jika span dimulai dengan span nilai, false bila tidak

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) fungsi

Memeriksa apakah span hanya-baca dimulai dengan span nilai yang dapat diubah yang ditentukan.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | The type of elements in the spans |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span hanya-baca yang akan diperiksa |
| value | const [Span](../../system/span/)\<T\>\& | Span yang dapat diubah yang berisi nilai untuk diperiksa |

### Nilai Kembali

true jika span dimulai dengan span nilai, false bila tidak

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) fungsi

Memeriksa apakah span karakter dimulai dengan span nilai yang ditentukan menggunakan perbandingan string.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Span karakter yang akan diperiksa |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Span karakter yang berisi nilai untuk diperiksa |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Jenis perbandingan string yang akan dilakukan |

### Nilai Kembali

true jika span dimulai dengan span nilai, false bila tidak

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<String\>\&, const char16_t *) fungsi

Memeriksa apakah span string dimulai dengan array karakter yang ditentukan.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<String> &span, const char16_t *val)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<[String](../../system/string/)\>\& | Span string yang akan diperiksa |
| val | const char16_t * | Array karakter yang akan diperiksa di awal |

### Nilai Kembali

true jika span dimulai dengan array karakter, false bila tidak

## Lihat Juga

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Class [String](../../system/string/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)