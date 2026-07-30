---
title: BinarySearchImpl()
second_title: Aspose.Slides pro C++ API Reference
description: Obecná implementace binárního vyhledávání.
type: docs
weight: 118
url: /cs/system.memoryextensions.details/binarysearchimpl/
---
## System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan\<T\>\&, const TValue&, TCompareFunc) funkce

Obecná implementace binárního vyhledávání.

```cpp
template<typename T,typename TValue,typename TCompareFunc> int32_t System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan<T> &span, const TValue &value, TCompareFunc compareFunc)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Type of elements in span |
| TValue | Type of value to search for |
| TCompareFunc | Function type for comparison |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span pro prohledávání |
| value | const TValue\& | Hodnota value k vyhledání |
| compareFunc | TCompareFunc | Funkce, která porovnává value se span prvkem a vrací **int32_t** (-1, 0, 1) |

### Návratová hodnota

[Index](../../system/index/) nalezeného prvku nebo bitový doplněk místa vložení

## Viz také

* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Jmenný prostor [System::MemoryExtensions::Details](../)
* Knihovna [Aspose.Slides](../../)