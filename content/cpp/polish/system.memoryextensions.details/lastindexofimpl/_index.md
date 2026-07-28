---
title: LastIndexOfImpl()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Znajduje ostatni indeks wartości w obszarze.
type: docs
weight: 14
url: /pl/system.memoryextensions.details/lastindexofimpl/
---
## System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan\<T\>\&, int32_t, const T\&) function


Znajduje ostatni indeks wartości w obszarze.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan<T> &searchSpace, int32_t length, const T &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w obszarze |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| searchSpace | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [Span](../../system/span/) do wyszukiwania |
| length | **int32_t** | Długość, w której należy szukać |
| value | const T\& | Wartość do znalezienia |

### Wartość zwracana

Ostatni indeks wartości, lub **-1** jeśli nie znaleziono

## Zobacz także

* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Przestrzeń nazw [System::MemoryExtensions::Details](../)
* Biblioteka [Aspose.Slides](../../)