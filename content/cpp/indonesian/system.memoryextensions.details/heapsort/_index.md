---
title: HeapSort()
second_title: Referensi API Aspose.Slides untuk C++
description: Melakukan heap sort pada pasangan kunci-nilai.
type: docs
weight: 79
url: /id/system.memoryextensions.details/heapsort/
---
## System::MemoryExtensions::Details::HeapSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) fungsi

Melakukan heap sort pada pasangan kunci-nilai.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::HeapSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| TKey | Tipe kunci |
| TValue | Tipe nilai |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Rentang kunci untuk diurutkan |
| values | [Span](../../system/span/)\<TValue\>\& | Rentang nilai untuk diurutkan |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) fungsi untuk kunci |

## Lihat Juga

* Kelas [Span](../../system/span/)
* Ruang Nama [System::MemoryExtensions::Details](../)
* Perpustakaan [Aspose.Slides](../../)