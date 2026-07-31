---
title: SwapIfGreaterWithValues()
second_title: Referensi API Aspose.Slides untuk C++
description: Menukar pasangan kunci-nilai bila kondisi perbandingan terpenuhi.
type: docs
weight: 53
url: /id/system.memoryextensions.details/swapifgreaterwithvalues/
---
## System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>, int32_t, int32_t) fungsi

Menukar pasangan kunci-nilai jika kondisi perbandingan terpenuhi.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer, int32_t i, int32_t j)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TKey | Tipe kunci |
| TValue | Tipe nilai |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Rentang kunci |
| values | [Span](../../system/span/)\<TValue\>\& | Rentang nilai |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) fungsi untuk kunci |
| i | **int32_t** | Indeks pertama untuk dibandingkan |
| j | **int32_t** | Indeks kedua untuk dibandingkan |

## Lihat Juga

* Kelas [Span](../../system/span/)
* Ruang nama [System::MemoryExtensions::Details](../)
* Perpustakaan [Aspose.Slides](../../)