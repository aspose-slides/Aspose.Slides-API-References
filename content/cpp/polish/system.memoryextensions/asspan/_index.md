---
title: AsSpan()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy span z tablicy.
type: docs
weight: 1
url: /pl/system.memoryextensions/asspan/
---
## System::MemoryExtensions::AsSpan(const ArrayPtr\<T\>\&, int32_t, int32_t) funkcja

Tworzy span z tablicy.

```cpp
template<typename T> Span<T> System::MemoryExtensions::AsSpan(const ArrayPtr<T> &array, int32_t start=0, int32_t length=-1)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w tablicy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| array | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | Tablica źródłowa. |
| start | **int32_t** | Początkowy indeks w tablicy. |
| length | **int32_t** | Długość span. |

### Wartość zwracana

Span<T> obejmujący określony fragment tablicy.

## System::MemoryExtensions::AsSpan(const String\&, int32_t, int32_t) funkcja

Tworzy span tylko do odczytu z łańcucha znaków.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::AsSpan(const String &text, int32_t start=0, int32_t length=-1)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| text | const [String](../../system/string/)\& | Łańcuch źródłowy. |
| start | **int32_t** | Początkowy indeks w łańcuchu. |
| length | **int32_t** | Długość span. |

### Wartość zwracana

ReadOnlySpan<char16_t> obejmujący określony fragment łańcucha.

## Zobacz także

* Definicja typu [ArrayPtr](../../system/arrayptr/)
* Klasa [Span](../../system/span/)
* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Klasa [String](../../system/string/)
* Przestrzeń nazw [System::MemoryExtensions](../)
* Biblioteka [Aspose.Slides](../../)