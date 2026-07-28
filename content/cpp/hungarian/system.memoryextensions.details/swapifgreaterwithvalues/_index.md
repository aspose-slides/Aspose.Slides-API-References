---
title: SwapIfGreaterWithValues()
second_title: Aspose.Slides C++ API Referencia
description: Kicseréli a kulcs-érték párokat, ha a összehasonlítási feltétel teljesül.
type: docs
weight: 53
url: /hu/system.memoryextensions.details/swapifgreaterwithvalues/
---
## System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>, int32_t, int32_t) függvény

Lecseréli a kulcs-érték párokat, ha a összehasonlítási feltétel teljesül.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer, int32_t i, int32_t j)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TKey | A kulcsok típusa |
| TValue | Az értékek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | A kulcsok span-ja |
| values | [Span](../../system/span/)\<TValue\>\& | Az értékek span-ja |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) függvény a kulcsokhoz |
| i | **int32_t** | Az első összehasonlítandó index |
| j | **int32_t** | A második összehasonlítandó index |

## Lásd még

* Osztály [Span](../../system/span/)
* Névtér [System::MemoryExtensions::Details](../)
* Könyvtár [Aspose.Slides](../../)