---
title: BinarySearchImpl()
second_title: Aspose.Slides für C++ API-Referenz
description: Allgemeine Implementierung der binären Suche.
type: docs
weight: 118
url: /de/system.memoryextensions.details/binarysearchimpl/
---
## System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan\<T\>\&, const TValue\&, TCompareFunc) Funktion


Allgemeine Implementierung der binären Suche.

```cpp
template<typename T,typename TValue,typename TCompareFunc> int32_t System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan<T> &span, const TValue &value, TCompareFunc compareFunc)
```


### Vorlagen-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ der Elemente im Span |
| TValue | Typ des zu suchenden Werts |
| TCompareFunc | Funktionstyp für den Vergleich |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zu durchsuchende Span |
| value | const TValue\& | Der zu suchende Wert |
| compareFunc | TCompareFunc | Funktion, die den Wert mit dem Span-Element vergleicht und **int32_t** (-1, 0, 1) zurückgibt |

### Rückgabewert

[Index](../../system/index/) des gefundenen Elements oder bitweises Komplement des Einfügepunktes

## Siehe auch

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Namensraum [System::MemoryExtensions::Details](../)
* Bibliothek [Aspose.Slides](../../)