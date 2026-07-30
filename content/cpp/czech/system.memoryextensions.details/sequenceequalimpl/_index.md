---
title: SequenceEqualImpl()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Kontroluje, zda jsou dva spany stejné od zadaných pozic.
type: docs
weight: 27
url: /cs/system.memoryextensions.details/sequenceequalimpl/
---
## System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan\<T\>\&, const int32_t, int32_t, const ReadOnlySpan\<T\>\&) funkce

Kontroluje, zda jsou dva spany (rozsahy) stejné od zadaných pozic.

```cpp
template<typename T> bool System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan<T> &first, const int32_t start, int32_t length, const ReadOnlySpan<T> &second)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanech |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | První span |
| start | const **int32_t** | Počáteční index v prvním spanu |
| length | **int32_t** | Počet prvků k porovnání |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Druhý span |

### Návratová hodnota

true, pokud jsou zadané rozsahy stejné, jinak false

## Viz také

* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Jmenný prostor [System::MemoryExtensions::Details](../)
* Knihovna [Aspose.Slides](../../)