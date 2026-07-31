---
title: Replace()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengganti semua kemunculan nilai dengan nilai baru dalam sebuah Span.
type: docs
weight: 287
url: /id/system.memoryextensions/replace/
---
## System::MemoryExtensions::Replace(Span\<T\>\&, const T\&, const T\&) fungsi

Mengganti semua kemunculan nilai dengan nilai baru dalam [Span](../../system/span/).

```cpp
template<typename T> void System::MemoryExtensions::Replace(Span<T> &span, const T &oldValue, const T &newValue)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | span yang akan dimodifikasi di tempat |
| oldValue | const T\& | nilai yang akan dicari dan diganti |
| newValue | const T\& | nilai baru untuk menggantikan oldValue |

## System::MemoryExtensions::Replace(const ReadOnlySpan\<T\>\&, Span\<T\>\&, const T\&, const T\&) fungsi

Menyalin elemen dari source ke destination, mengganti nilai yang ditentukan selama penyalinan.

```cpp
template<typename T> void System::MemoryExtensions::Replace(const ReadOnlySpan<T> &source, Span<T> &destination, const T &oldValue, const T &newValue)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | source [ReadOnlySpan](../../system/readonlyspan/) untuk disalin dari |
| destination | [Span](../../system/span/)\<T\>\& | destination [Span](../../system/span/) untuk disalin ke |
| oldValue | const T\& | nilai yang akan dicari dan diganti selama penyalinan |
| newValue | const T\& | nilai baru untuk menggantikan oldValue |

## Lihat Juga

* Kelas [Span](../../system/span/)
* Kelas [ReadOnlySpan](../../system/readonlyspan/)
* Ruang nama [System::MemoryExtensions](../)
* Pustaka [Aspose.Slides](../../)