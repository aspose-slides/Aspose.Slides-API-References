---
title: IndexOf()
second_title: Aspose.Slides für C++ API-Referenz
description: Findet den Index eines ReadOnlySpan<T>-Werts in einem anderen ReadOnlySpan<T>
type: docs
weight: 144
url: /de/system.memoryextensions/indexof/
---
## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion

Findet den Index eines ReadOnlySpan<T>-Werts in einem anderen ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | The type of elements in the spans |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zu durchsuchende Span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zu suchende Wert |

### Rückgabewert

Der nullbasierte Index des ersten Vorkommens oder -1, falls nicht gefunden

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const T\&) Funktion

Findet den Index eines einzelnen Werts in einem ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const T &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | The type of elements in the span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zu durchsuchende Span |
| value | const T\& | Der zu suchende Wert |

### Rückgabewert

Der nullbasierte Index des ersten Vorkommens oder -1, falls nicht gefunden

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion

Findet den Index eines ReadOnlySpan<T>-Werts in einem Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | The type of elements in the spans |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der zu durchsuchende Span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zu suchende Wert |

### Rückgabewert

Der nullbasierte Index des ersten Vorkommens oder -1, falls nicht gefunden

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const T\&) Funktion

Findet den Index eines einzelnen Werts in einem Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const T &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | The type of elements in the span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der zu durchsuchende Span |
| value | const T\& | Der zu suchende Wert |

### Rückgabewert

Der nullbasierte Index des ersten Vorkommens oder -1, falls nicht gefunden

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) Funktion

Findet den Index eines ReadOnlySpan<char16_t>-Werts in einem ReadOnlySpan<char16_t> mit StringComparison.

```cpp
int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Der zu durchsuchende Span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Der zu suchende Wert |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Der zu verwendende StringComparison-Typ |

### Rückgabewert

Der nullbasierte Index des ersten Vorkommens oder -1, falls nicht gefunden

## Siehe auch

* Enum [StringComparison](../../system/stringcomparison/)
* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Namensraum [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)