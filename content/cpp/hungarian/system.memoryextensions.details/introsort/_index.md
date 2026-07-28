---
title: IntroSort()
second_title: Aspose.Slides C++ API referenciája
description: Az introsort algoritmus kulcs-érték párokra vonatkozó belső megvalósítása.
type: docs
weight: 40
url: /hu/system.memoryextensions.details/introsort/
---
## System::MemoryExtensions::Details::IntroSort(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) function


Az introsort algoritmus kulcs-érték párokra vonatkozó belső megvalósítása.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::IntroSort(Span<TKey> &keys, Span<TValue> &values, int32_t depthLimit, std::function<int32_t(const TKey &, const TKey &)> comparer)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TKey | A kulcsok típusa |
| TValue | Az értékek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | A rendezendő kulcsok span-ja |
| values | [Span](../../system/span/)\<TValue\>\& | A rendezendő értékek span-ja |
| depthLimit | **int32_t** | A legnagyobb rekurziós mélység a heapsort-ra váltás előtt |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) függvény a kulcsokhoz |

## Lásd még

* Osztály [Span](../../system/span/)
* Névterület [System::MemoryExtensions::Details](../)
* Könyvtár [Aspose.Slides](../../)