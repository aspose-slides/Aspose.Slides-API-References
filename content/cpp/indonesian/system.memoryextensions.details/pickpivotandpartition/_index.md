---
title: PickPivotAndPartition()
second_title: Referensi API Aspose.Slides untuk C++
description: Memilih pivot dan membagi pasangan kunci-nilai untuk quicksort.
type: docs
weight: 105
url: /id/system.memoryextensions.details/pickpivotandpartition/
---
## System::MemoryExtensions::Details::PickPivotAndPartition(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) fungsi

Memilih pivot dan membagi pasangan kunci-nilai untuk quicksort.

```cpp
template<typename TKey,typename TValue> int32_t System::MemoryExtensions::Details::PickPivotAndPartition(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TKey | Jenis kunci |
| TValue | Jenis nilai |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Rentang kunci untuk dibagi |
| values | [Span](../../system/span/)\<TValue\>\& | Rentang nilai untuk dibagi |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) function untuk kunci |

### Nilai Kembali

Indeks pivot setelah pembagian

## Lihat Juga

* Kelas [Span](../../system/span/)
* Ruang Nama [System::MemoryExtensions::Details](../)
* Pustaka [Aspose.Slides](../../)