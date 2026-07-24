---
title: Contains()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft, ob ein schreibgeschützter Span einen bestimmten Wert enthält.
type: docs
weight: 40
url: /de/system.memoryextensions/contains/
---
## System::MemoryExtensions::Contains(const ReadOnlySpan\<T\>\&, const T\&) Funktion

Überprüft, ob ein schreibgeschützter Span einen bestimmten Wert enthält.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const ReadOnlySpan<T> &span, const T &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der Span, in dem gesucht wird |
| value | const T\& | Der zu suchende Wert |

### Rückgabewert

true, wenn der Wert im Span gefunden wurde, sonst false

## System::MemoryExtensions::Contains(const Span\<T\>\&, const T\&) Funktion

Überprüft, ob ein veränderbarer Span einen bestimmten Wert enthält.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const Span<T> &span, const T &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der veränderbare Span, in dem gesucht wird |
| value | const T\& | Der zu suchende Wert |

### Rückgabewert

true, wenn der Wert im Span gefunden wurde, sonst false

## System::MemoryExtensions::Contains(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) Funktion

Überprüft, ob ein Zeichen-Span einen anderen Zeichen-Span mit angegebenen Vergleichsregeln enthält.

```cpp
bool System::MemoryExtensions::Contains(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Der Span, in dem gesucht wird |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Der gesuchte Span |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Der Typ des durchzuführenden String-Vergleichs |

### Rückgabewert

true, wenn der Wert im Span gefunden wurde, sonst false

## Siehe auch

* Enum [StringComparison](../../system/stringcomparison/)
* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Namensraum [System::MemoryExtensions](../)
* Bibliothek [Aspose.Slides](../../)