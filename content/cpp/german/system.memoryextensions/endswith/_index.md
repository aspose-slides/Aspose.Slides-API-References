---
title: EndsWith()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob ein ReadOnlySpan<T> mit einem einzelnen Wert endet.
type: docs
weight: 131
url: /de/system.memoryextensions/endswith/
---
## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const T\&) Funktion

Bestimmt, ob ein ReadOnlySpan<T> mit einem einzelnen Wert endet.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const T &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zu prüfende Span |
| value | const T\& | Der Wert, nach dem am Ende des Spans gesucht wird |

### Rückgabewert

true, wenn der Span mit dem Wert endet, sonst false

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion

Bestimmt, ob ein ReadOnlySpan<T> mit einem anderen ReadOnlySpan<T> endet.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente in den Spans |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zu prüfende Span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der Span, nach dem am Ende des Ziel-Spans gesucht wird |

### Rückgabewert

true, wenn der Span mit dem Wert-Span endet, sonst false

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion

Bestimmt, ob ein Span<T> mit einem ReadOnlySpan<T> endet.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente in den Spans |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der zu prüfende Span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der Span, nach dem am Ende des Ziel-Spans gesucht wird |

### Rückgabewert

true, wenn der Span mit dem Wert-Span endet, sonst false

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) Funktion

Bestimmt, ob ein ReadOnlySpan<T> mit einem Span<T> endet.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente in den Spans |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zu prüfende Span |
| value | const [Span](../../system/span/)\<T\>\& | Der Span, nach dem am Ende des Ziel-Spans gesucht wird |

### Rückgabewert

true, wenn der Span mit dem Wert-Span endet, sonst false

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const Span\<T\>\&) Funktion

Bestimmt, ob ein Span<T> mit einem anderen Span<T> endet.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const Span<T> &value)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente in den Spans |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der zu prüfende Span |
| value | const [Span](../../system/span/)\<T\>\& | Der Span, nach dem am Ende des Ziel-Spans gesucht wird |

### Rückgabewert

true, wenn der Span mit dem Wert-Span endet, sonst false

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) Funktion

Bestimmt, ob ein ReadOnlySpan<char16_t> mit dem angegebenen Wert endet, unter Verwendung von StringComparison.

```cpp
bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Der zu prüfende Span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Der Wert, nach dem am Ende des Spans gesucht wird |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Der zu verwendende Stringvergleichstyp |

### Rückgabewert

true, wenn der Span mit dem Wert endet, sonst false

## Siehe auch

* Enum [StringComparison](../../system/stringcomparison/)
* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Namensraum [System::MemoryExtensions](../)
* Bibliothek [Aspose.Slides](../../)