---
title: InsertionSort()
second_title: Aspose.Slides C++ API referencia
description: Beszúró rendezést hajt végre kulcs-érték párokon.
type: docs
weight: 66
url: /hu/system.memoryextensions.details/insertionsort/
---
## System::MemoryExtensions::Details::InsertionSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) függvény


Beszúró rendezést hajt végre kulcs-érték párokon.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::InsertionSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TKey | A kulcsok típusa |
| TValue | Az értékek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | A rendezendő kulcsok spanne |
| values | [Span](../../system/span/)\<TValue\>\& | A rendezendő értékek spanne |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) függvény a kulcsokhoz |

## Lásd még

* Osztály [Span](../../system/span/)
* Névtér [System::MemoryExtensions::Details](../)
* Könyvtár [Aspose.Slides](../../)