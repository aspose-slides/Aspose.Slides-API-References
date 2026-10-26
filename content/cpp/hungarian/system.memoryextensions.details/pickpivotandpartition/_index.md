---
title: PickPivotAndPartition()
second_title: Aspose.Slides C++ API referencia
description: Kiválasztja a pivot elemet és felosztja a kulcs-érték párokat gyorsrendezéshez.
type: docs
weight: 105
url: /hu/system.memoryextensions.details/pickpivotandpartition/
---
## System::MemoryExtensions::Details::PickPivotAndPartition(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) függvény

Kiválasztja a pivot elemet és felosztja a kulcs-érték párokat gyorsrendezéshez.

```cpp
template<typename TKey,typename TValue> int32_t System::MemoryExtensions::Details::PickPivotAndPartition(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| TKey | A kulcsok típusa |
| TValue | Az értékek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | A felosztandó kulcsok tartománya |
| values | [Span](../../system/span/)\<TValue\>\& | A felosztandó értékek tartománya |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) függvény a kulcsokhoz |

### Visszatérési érték

A pivot index a felosztás után

## Lásd még

* Osztály [Span](../../system/span/)
* Névtér [System::MemoryExtensions::Details](../)
* Könyvtár [Aspose.Slides](../../)