---
title: InsertionSort()
second_title: Referensi API Aspose.Slides untuk C++
description: Melakukan insertion sort pada pasangan kunci-nilai.
type: docs
weight: 66
url: /id/system.memoryextensions.details/insertionsort/
---
## System::MemoryExtensions::Details::InsertionSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) fungsi


Melakukan insertion sort pada pasangan kunci-nilai.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::InsertionSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
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
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) fungsi untuk kunci |

## Lihat Juga

* Kelas [Span](../../system/span/)
* Ruang nama [System::MemoryExtensions::Details](../)
* Perpustakaan [Aspose.Slides](../../)