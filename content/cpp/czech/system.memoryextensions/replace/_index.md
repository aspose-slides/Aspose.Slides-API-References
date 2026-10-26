---
title: Replace()
second_title: Aspose.Slides pro C++ API Reference
description: Nahrazuje všechny výskyty hodnoty novou hodnotou v Span.
type: docs
weight: 287
url: /cs/system.memoryextensions/replace/
---
## System::MemoryExtensions::Replace(Span\<T\>\&, const T\&, const T\&) funkce

Nahrazuje všechny výskyty hodnoty novou hodnotou v [Span](../../system/span/).

```cpp
template<typename T> void System::MemoryExtensions::Replace(Span<T> &span, const T &oldValue, const T &newValue)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Span, který se má upravit přímo |
| oldValue | const T\& | Hodnota, která se má vyhledat a nahradit |
| newValue | const T\& | Nová hodnota, kterou nahradí oldValue |

## System::MemoryExtensions::Replace(const ReadOnlySpan\<T\>\&, Span\<T\>\&, const T\&, const T\&) funkce

Kopíruje prvky ze zdroje do cíle a během kopírování nahrazuje zadané hodnoty.

```cpp
template<typename T> void System::MemoryExtensions::Replace(const ReadOnlySpan<T> &source, Span<T> &destination, const T &oldValue, const T &newValue)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanech |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zdrojový [ReadOnlySpan](../../system/readonlyspan/) ze kterého se kopíruje |
| destination | [Span](../../system/span/)\<T\>\& | Cílový [Span](../../system/span/) do kterého se kopíruje |
| oldValue | const T\& | Hodnota, která se má během kopírování vyhledat a nahradit |
| newValue | const T\& | Nová hodnota, kterou nahradí oldValue |

## Viz také

* Třída [Span](../../system/span/)
* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Jmenný prostor [System::MemoryExtensions](../)
* Knihovna [Aspose.Slides](../../)