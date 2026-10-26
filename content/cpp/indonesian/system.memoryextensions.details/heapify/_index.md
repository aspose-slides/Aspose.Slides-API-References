---
title: Heapify()
second_title: Referensi API Aspose.Slides untuk C++
description: Mempertahankan properti heap untuk pasangan kunci-nilai.
type: docs
weight: 92
url: /id/system.memoryextensions.details/heapify/
---
## System::MemoryExtensions::Details::Heapify(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) fungsi


Mempertahankan sifat heap untuk pasangan kunci-nilai.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::Heapify(Span<TKey> &keys, Span<TValue> &values, int32_t n, int32_t i, std::function<int32_t(const TKey &, const TKey &)> comparer)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TKey | Tipe kunci |
| TValue | Tipe nilai |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Rentang kunci dalam heap |
| values | [Span](../../system/span/)\<TValue\>\& | Rentang nilai dalam heap |
| n | **int32_t** | Ukuran heap |
| i | **int32_t** | [Index](../../system/index/) untuk heapify dari |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) fungsi untuk kunci |

## Lihat Juga

* Kelas [Span](../../system/span/)
* Namespace [System::MemoryExtensions::Details](../)
* Pustaka [Aspose.Slides](../../)