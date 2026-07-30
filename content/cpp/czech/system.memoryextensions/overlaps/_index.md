---
title: Overlaps()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Určuje, zda se dva ReadOnlySpany překrývají v paměti bez výpočtu offsetu.
type: docs
weight: 274
url: /cs/system.memoryextensions/overlaps/
---
## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funkce

Určuje, zda se dva ReadOnlySpany překrývají v paměti bez výpočtu offsetu.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanech |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | První span pro kontrolu překrytí |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Druhý span pro kontrolu překrytí |

### Návratová hodnota

true, pokud spany sdílejí jakékoli společné paměťové umístění, false jinak

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funkce

Určuje, zda se [Span](../../system/span/) a [ReadOnlySpan](../../system/readonlyspan/) překrývají v paměti bez výpočtu offsetu.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanech |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) pro kontrolu překrytí |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) pro kontrolu překrytí |

### Návratová hodnota

true, pokud spany sdílejí jakékoli společné paměťové umístění, false jinak

## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) funkce

Určuje, zda se dva ReadOnlySpany překrývají v paměti a vypočítá offset.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanech |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | První span pro kontrolu překrytí |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Druhý span pro kontrolu překrytí |
| elementOffset | **int32_t**\& | Výstupní parametr, který získá offset mezi spany, pokud se překrývají |

### Návratová hodnota

true, pokud spany sdílejí jakékoli společné paměťové umístění, false jinak

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) funkce

Určuje, zda se [Span](../../system/span/) a [ReadOnlySpan](../../system/readonlyspan/) překrývají v paměti a vypočítá offset.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanech |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) pro kontrolu překrytí |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) pro kontrolu překrytí |
| elementOffset | **int32_t**\& | Výstupní parametr, který získá offset mezi spany, pokud se překrývají |

### Návratová hodnota

true, pokud spany sdílejí jakékoli společné paměťové umístění, false jinak

## Viz také

* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Třída [Span](../../system/span/)
* Jmenný prostor [System::MemoryExtensions](../)
* Knihovna [Aspose.Slides](../../)