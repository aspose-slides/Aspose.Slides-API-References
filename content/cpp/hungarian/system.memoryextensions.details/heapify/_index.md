---
title: Heapify()
second_title: Aspose.Slides C++ API referencia
description: Fenntartja a kupac tulajdonságát a kulcs-érték párok számára.
type: docs
weight: 92
url: /hu/system.memoryextensions.details/heapify/
---
## System::MemoryExtensions::Details::Heapify(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) függvény


Fenntartja a kupac tulajdonságát a kulcs-érték párok számára.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::Heapify(Span<TKey> &keys, Span<TValue> &values, int32_t n, int32_t i, std::function<int32_t(const TKey &, const TKey &)> comparer)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| TKey | A kulcsok típusa |
| TValue | Az értékek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | A kupacban lévő kulcsok span-ja |
| values | [Span](../../system/span/)\<TValue\>\& | A kupacban lévő értékek span-ja |
| n | **int32_t** | A kupac mérete |
| i | **int32_t** | [Index](../../system/index/) a kupacra rendezéshez |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) függvény a kulcsokhoz |

## Lásd még

* Osztály [Span](../../system/span/)
* Névterület [System::MemoryExtensions::Details](../)
* Könyvtár [Aspose.Slides](../../)