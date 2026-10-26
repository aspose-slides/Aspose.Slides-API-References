---
title: AsSpan()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří span z pole.
type: docs
weight: 1
url: /cs/system.memoryextensions/asspan/
---
## System::MemoryExtensions::AsSpan(const ArrayPtr\<T\>\&, int32_t, int32_t) funkce

Vytvoří span z pole.

```cpp
template<typename T> Span<T> System::MemoryExtensions::AsSpan(const ArrayPtr<T> &array, int32_t start=0, int32_t length=-1)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků v poli. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| array | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | Zdrojové pole. |
| start | **int32_t** | Počáteční index v poli. |
| length | **int32_t** | Délka spanu. |

### Návratová hodnota

Span<T> představující určenou část pole.

## System::MemoryExtensions::AsSpan(const String\&, int32_t, int32_t) funkce

Vytvoří span pouze pro čtení z řetězce.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::AsSpan(const String &text, int32_t start=0, int32_t length=-1)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| text | const [String](../../system/string/)\& | Zdrojový řetězec. |
| start | **int32_t** | Počáteční index v řetězci. |
| length | **int32_t** | Délka spanu. |

### Návratová hodnota

ReadOnlySpan<char16_t> představující určenou část řetězce.

## Viz také

* Typedef [ArrayPtr](../../system/arrayptr/)
* Třída [Span](../../system/span/)
* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Třída [String](../../system/string/)
* Jmenný prostor [System::MemoryExtensions](../)
* Knihovna [Aspose.Slides](../../)