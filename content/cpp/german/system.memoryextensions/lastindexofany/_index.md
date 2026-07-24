---
title: LastIndexOfAny()
second_title: Aspose.Slides für C++ API-Referenz
description: Findet das letzte Vorkommen eines von drei angegebenen Werten innerhalb eines Span.
type: docs
weight: 222
url: /de/system.memoryextensions/lastindexofany/
---
## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) Funktion

Findet das letzte Vorkommen eines von drei angegebenen Werten innerhalb eines Span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | The type of elements in the span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to search for |
| value1 | const T\& | The second value to search for |
| value2 | const T\& | The third value to search for |

### Rückgabewert

Der nullbasierte Index des letzten Vorkommens oder -1, falls nicht gefunden

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) Funktion

Findet das letzte Vorkommen eines von drei angegebenen Werten innerhalb eines veränderlichen Span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | The type of elements in the span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to search for |
| value1 | const T\& | The second value to search for |
| value2 | const T\& | The third value to search for |

### Rückgabewert

Der nullbasierte Index des letzten Vorkommens oder -1, falls nicht gefunden

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) Funktion

Findet das letzte Vorkommen eines von zwei angegebenen Werten innerhalb eines Span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | The type of elements in the span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to search for |
| value1 | const T\& | The second value to search for |

### Rückgabewert

Der nullbasierte Index des letzten Vorkommens oder -1, falls nicht gefunden

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&) Funktion

Findet das letzte Vorkommen eines von zwei angegebenen Werten innerhalb eines veränderlichen Span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | The type of elements in the span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to search for |
| value1 | const T\& | The second value to search for |

### Rückgabewert

Der nullbasierte Index des letzten Vorkommens oder -1, falls nicht gefunden

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion

Findet das letzte Vorkommen eines beliebigen Wertes aus einer Sequenz innerhalb eines Span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | The type of elements in the span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence of values to search for |

### Rückgabewert

Der nullbasierte Index des letzten Vorkommens oder -1, falls nicht gefunden

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion

Findet das letzte Vorkommen eines beliebigen Wertes aus einer Sequenz innerhalb eines veränderlichen Span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | The type of elements in the span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence of values to search for |

### Rückgabewert

Der nullbasierte Index des letzten Vorkommens oder -1, falls nicht gefunden

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const Span\<T\>\&) Funktion

Findet das letzte Vorkommen eines beliebigen Wertes aus einer veränderlichen Sequenz innerhalb eines veränderlichen Span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const Span<T> &values)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | The type of elements in the span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| values | const [Span](../../system/span/)\<T\>\& | The sequence of values to search for |

### Rückgabewert

Der nullbasierte Index des letzten Vorkommens oder -1, falls nicht gefunden

## Siehe auch

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Namensraum [System::MemoryExtensions](../)
* Bibliothek [Aspose.Slides](../../)