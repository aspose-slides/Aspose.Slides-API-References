---
title: BinarySearchImpl()
second_title: Referensi API Aspose.Slides untuk C++
description: Implementasi pencarian biner umum.
type: docs
weight: 118
url: /id/system.memoryextensions.details/binarysearchimpl/
---
## System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan\<T\>\&, const TValue\&, TCompareFunc) fungsi

Implementasi pencarian biner umum.

```cpp
template<typename T,typename TValue,typename TCompareFunc> int32_t System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan<T> &span, const TValue &value, TCompareFunc compareFunc)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam span |
| TValue | Tipe nilai yang dicari |
| TCompareFunc | Tipe fungsi untuk perbandingan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span untuk pencarian |
| value | const TValue\& | Nilai yang dicari |
| compareFunc | TCompareFunc | Fungsi yang membandingkan nilai dengan elemen span dan mengembalikan **int32_t** (-1, 0, 1) |

### Nilai Kembalian

[Index](../../system/index/) elemen yang ditemukan atau komplemen bitwise dari titik sisipan

## Lihat Juga

* Kelas [ReadOnlySpan](../../system/readonlyspan/)
* Ruang nama [System::MemoryExtensions::Details](../)
* Pustaka [Aspose.Slides](../../)