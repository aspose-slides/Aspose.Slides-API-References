---
title: LastIndexOfImpl()
second_title: Referensi API Aspose.Slides untuk C++
description: Menemukan indeks terakhir dari sebuah nilai dalam span.
type: docs
weight: 14
url: /id/system.memoryextensions.details/lastindexofimpl/
---
## System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan\<T\>\&, int32_t, const T\&) function

Menemukan indeks terakhir dari sebuah nilai dalam span.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan<T> &searchSpace, int32_t length, const T &value)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Tipe elemen dalam span |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| searchSpace | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [Span](../../system/span/) untuk dicari |
| length | **int32_t** | Panjang untuk dicari di dalam |
| value | const T\& | Nilai yang dicari |

### Nilai Kembalian

Indeks terakhir dari nilai, atau -1 jika tidak ditemukan

## Lihat Juga

* Kelas [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions::Details](../)
* Perpustakaan [Aspose.Slides](../../)