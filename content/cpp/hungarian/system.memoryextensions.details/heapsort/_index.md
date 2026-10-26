---
title: HeapSort()
second_title: Aspose.Slides C++ API hivatkozás
description: Kupacrendezést hajt végre kulcs-érték párokon.
type: docs
weight: 79
url: /hu/system.memoryextensions.details/heapsort/
---
## System::MemoryExtensions::Details::HeapSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) függvény

Heap sortot hajt végre kulcs-érték párokon.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::HeapSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TKey | A kulcsok típusa |
| TValue | Az értékek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | A rendezendő kulcsok spannja |
| values | [Span](../../system/span/)\<TValue\>\& | A rendezendő értékek spannja |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) függvény a kulcsokhoz |

## Lásd még

* Osztály [Span](../../system/span/)
* Névterület [System::MemoryExtensions::Details](../)
* Könyvtár [Aspose.Slides](../../)