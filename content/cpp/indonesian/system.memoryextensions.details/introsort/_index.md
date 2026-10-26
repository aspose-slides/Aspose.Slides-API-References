---
title: IntroSort()
second_title: Referensi API Aspose.Slides untuk C++
description: Implementasi internal algoritma introsort untuk pasangan kunci-nilai.
type: docs
weight: 40
url: /id/system.memoryextensions.details/introsort/
---
## System::MemoryExtensions::Details::IntroSort(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) fungsi

Implementasi internal algoritma introsort untuk pasangan kunci-nilai.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::IntroSort(Span<TKey> &keys, Span<TValue> &values, int32_t depthLimit, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TKey | Tipe kunci |
| TValue | Tipe nilai |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Rentang kunci untuk diurutkan |
| values | [Span](../../system/span/)\<TValue\>\& | Rentang nilai untuk diurutkan |
| depthLimit | **int32_t** | Kedalaman rekursi maksimum sebelum beralih ke heapsort |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) fungsi untuk kunci |

## Lihat Juga

* Kelas [Span](../../system/span/)
* Namespace [System::MemoryExtensions::Details](../)
* Pustaka [Aspose.Slides](../../)