---
title: BinarySearchImpl()
second_title: Aspose.Slides C++ API referencia
description: Általános bináris keresés megvalósítása.
type: docs
weight: 118
url: /hu/system.memoryextensions.details/binarysearchimpl/
---
## System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan\<T\>\&, const TValue\&, TCompareFunc) függvény


Általános bináris keresés megvalósítás.

```cpp
template<typename T,typename TValue,typename TCompareFunc> int32_t System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan<T> &span, const TValue &value, TCompareFunc compareFunc)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A span elemeinek típusa |
| TValue | A keresett érték típusa |
| TCompareFunc | Összehasonlító függvény típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | A keresendő span |
| value | const TValue\& | A keresett érték |
| compareFunc | TCompareFunc | Függvény, amely összehasonlítja az értéket a span elemmel és **int32_t**-t ad vissza (-1, 0, 1) |

### Visszatérési érték

[Index](../../system/index/) a megtalált elem vagy a beszúrási pont bitenkénti kiegészítése

## Lásd még

* Osztály [ReadOnlySpan](../../system/readonlyspan/)
* Névtere [System::MemoryExtensions::Details](../)
* Könyvtár [Aspose.Slides](../../)