---
title: Replace()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zastępuje wszystkie wystąpienia wartości nową wartością w obiekcie Span.
type: docs
weight: 287
url: /pl/system.memoryextensions/replace/
---
## System::MemoryExtensions::Replace(Span\<T\>\&, const T\&, const T\&) funkcja


Zastępuje wszystkie wystąpienia wartości nową wartością w [Span](../../system/span/).

```cpp
template<typename T> void System::MemoryExtensions::Replace(Span<T> &span, const T &oldValue, const T &newValue)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w span |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | span do modyfikacji w miejscu |
| oldValue | const T\& | Wartość do wyszukania i zastąpienia |
| newValue | const T\& | Nowa wartość, która zastępuje oldValue |

## System::MemoryExtensions::Replace(const ReadOnlySpan\<T\>\&, Span\<T\>\&, const T\&, const T\&) funkcja


Kopiuje elementy ze źródła do miejsca docelowego, zastępując określone wartości podczas kopiowania.

```cpp
template<typename T> void System::MemoryExtensions::Replace(const ReadOnlySpan<T> &source, Span<T> &destination, const T &oldValue, const T &newValue)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w spans |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Źródłowy [ReadOnlySpan](../../system/readonlyspan/) do skopiowania |
| destination | [Span](../../system/span/)\<T\>\& | Docelowy [Span](../../system/span/) do skopiowania |
| oldValue | const T\& | Wartość do wyszukania i zastąpienia podczas kopiowania |
| newValue | const T\& | Nowa wartość, która zastępuje oldValue |

## Zobacz także

* Klasa [Span](../../system/span/)
* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Przestrzeń nazw [System::MemoryExtensions](../)
* Biblioteka [Aspose.Slides](../../)