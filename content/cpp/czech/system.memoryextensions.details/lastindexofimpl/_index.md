---
title: LastIndexOfImpl()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Najde poslední index hodnoty ve spanu.
type: docs
weight: 14
url: /cs/system.memoryextensions.details/lastindexofimpl/
---
## System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan\<T\>\&, int32_t, const T\&) funkce


Nalézá poslední index hodnoty ve spanu.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan<T> &searchSpace, int32_t length, const T &value)
```


### Parametry šablony

| Parameter | Description |
| --- | --- |
| T | Typ prvků ve spanu |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| searchSpace | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [Span](../../system/span/) k vyhledání |
| length | **int32_t** | Délka, ve které se hledá |
| value | const T\& | Hodnota k nalezení |

### Návratová hodnota

Poslední index hodnoty nebo -1, pokud nebyl nalezen

## Viz také

* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Jmenný prostor [System::MemoryExtensions::Details](../)
* Knihovna [Aspose.Slides](../../)