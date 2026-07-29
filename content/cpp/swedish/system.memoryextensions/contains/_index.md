---
title: Contains()
second_title: Aspose.Slides för C++ API-referens
description: Kontrollerar om ett read-only-spann innehåller ett specifikt värde.
type: docs
weight: 40
url: /sv/system.memoryextensions/contains/
---
## System::MemoryExtensions::Contains(const ReadOnlySpan\<T\>\&, const T\&) funktion


Kontrollerar om ett read-only-spann innehåller ett specifikt värde.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const ReadOnlySpan<T> &span, const T &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spannet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Spannet att söka i |
| value | const T\& | Värdet att söka efter |

### Returvärde

Sant om värdet hittas i spannet, falskt annars

## System::MemoryExtensions::Contains(const Span\<T\>\&, const T\&) funktion


Kontrollerar om ett muterbart spann innehåller ett specifikt värde.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const Span<T> &span, const T &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spannet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Det muterbara spannet att söka i |
| value | const T\& | Värdet att söka efter |

### Returvärde

Sant om värdet hittas i spannet, falskt annars

## System::MemoryExtensions::Contains(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) funktion


Kontrollerar om ett tecken-spann innehåller ett annat tecken-spann med angivna jämförelseregler.

```cpp
bool System::MemoryExtensions::Contains(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Spannet att söka i |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Spannet att söka efter |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Typen av strängjämförelse att utföra |

### Returvärde

Sant om värdet hittas i spannet, falskt annars

## Se även

* Enum [StringComparison](../../system/stringcomparison/)
* Klass [ReadOnlySpan](../../system/readonlyspan/)
* Klass [Span](../../system/span/)
* Namnrymd [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)