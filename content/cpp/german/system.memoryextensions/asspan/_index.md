---
title: AsSpan()
second_title: Aspose.Slides für C++ API Referenz
description: Erzeugt einen Span aus einem Array.
type: docs
weight: 1
url: /de/system.memoryextensions/asspan/
---
## System::MemoryExtensions::AsSpan(const ArrayPtr\<T\>\&, int32_t, int32_t) Funktion

Erzeugt einen Span aus einem Array.

```cpp
template<typename T> Span<T> System::MemoryExtensions::AsSpan(const ArrayPtr<T> &array, int32_t start=0, int32_t length=-1)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Array. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | Das Quell-Array. |
| start | **int32_t** | Der Startindex im Array. |
| length | **int32_t** | Die Länge des Span. |

### Rückgabewert

Span<T>, der den angegebenen Teil des Arrays abdeckt.

## System::MemoryExtensions::AsSpan(const String\&, int32_t, int32_t) Funktion

Erzeugt einen schreibgeschützten Span aus einer Zeichenkette.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::AsSpan(const String &text, int32_t start=0, int32_t length=-1)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | const [String](../../system/string/)\& | Die Quell-Zeichenkette. |
| start | **int32_t** | Der Startindex in der Zeichenkette. |
| length | **int32_t** | Die Länge des Span. |

### Rückgabewert

ReadOnlySpan<char16_t>, der den angegebenen Teil der Zeichenkette abdeckt.

## Siehe auch

* Typedef [ArrayPtr](../../system/arrayptr/)
* Class [Span](../../system/span/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [String](../../system/string/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)