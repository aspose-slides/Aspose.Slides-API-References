---
title: LastIndexOf()
second_title: Aspose.Slides für C++ API-Referenz
description: Findet das letzte Vorkommen einer Sequenz innerhalb eines Spans.
type: docs
weight: 209
url: /de/system.memoryextensions/lastindexof/
---
## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion

Findet das letzte Vorkommen einer Sequenz innerhalb eines Spans.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der Span, in dem gesucht wird |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Die zu suchende Sequenz |

### Rückgabewert

Der nullbasierte Index des letzten Vorkommens oder -1, falls nicht gefunden

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const T\&) Funktion

Findet das letzte Vorkommen eines einzelnen Werts innerhalb eines Spans.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const T &value)
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

Der nullbasierte Index des letzten Vorkommens oder -1, falls nicht gefunden

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion

Findet das letzte Vorkommen einer Sequenz innerhalb eines veränderlichen Spans.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der Span, in dem gesucht wird |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Die zu suchende Sequenz |

### Rückgabewert

Der nullbasierte Index des letzten Vorkommens oder -1, falls nicht gefunden

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const T\&) Funktion

Findet das letzte Vorkommen eines einzelnen Werts innerhalb eines veränderlichen Spans.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const T &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der Span, in dem gesucht wird |
| value | const T\& | Der zu suchende Wert |

### Rückgabewert

Der nullbasierte Index des letzten Vorkommens oder -1, falls nicht gefunden

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) Funktion

Findet das letzte Vorkommen eines Werts innerhalb eines Spans mithilfe des angegebenen Stringvergleichs.

```cpp
int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Der Span, in dem gesucht wird |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Der zu suchende Wert |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Der Typ des durchzuführenden Stringvergleichs |

### Rückgabewert

Der nullbasierte Index des letzten Vorkommens oder -1, falls nicht gefunden

## Siehe auch

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)