---
title: ContainsAny()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft, ob ein schreibgeschützter Span einen von zwei Werten enthält.
type: docs
weight: 53
url: /de/system.memoryextensions/containsany/
---
## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) Funktion

Prüft, ob ein schreibgeschützter Span einen von zwei Werten enthält.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der Span, in dem gesucht wird |
| value0 | const T\& | Der erste zu suchende Wert |
| value1 | const T\& | Der zweite zu suchende Wert |

### Rückgabewert

true, wenn einer der Werte im Span gefunden wird, sonst false

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) Funktion

Prüft, ob ein schreibgeschützter Span einen von drei Werten enthält.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der Span, in dem gesucht wird |
| value0 | const T\& | Der erste zu suchende Wert |
| value1 | const T\& | Der zweite zu suchende Wert |
| value2 | const T\& | Der dritte zu suchende Wert |

### Rückgabewert

true, wenn einer der Werte im Span gefunden wird, sonst false

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&) Funktion

Prüft, ob ein veränderbarer Span einen von zwei Werten enthält.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der veränderbare Span, in dem gesucht wird |
| value0 | const T\& | Der erste zu suchende Wert |
| value1 | const T\& | Der zweite zu suchende Wert |

### Rückgabewert

true, wenn einer der Werte im Span gefunden wird, sonst false

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&, const T\&) Funktion

Prüft, ob ein veränderbarer Span einen von drei Werten enthält.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der veränderbare Span, in dem gesucht wird |
| value0 | const T\& | Der erste zu suchende Wert |
| value1 | const T\& | Der zweite zu suchende Wert |
| value2 | const T\& | Der dritte zu suchende Wert |

### Rückgabewert

true, wenn einer der Werte im Span gefunden wird, sonst false

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion

Prüft, ob ein schreibgeschützter Span einen beliebigen Wert aus einem anderen Span enthält.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente in den Spans |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der Span, in dem gesucht wird |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der Span der zu suchenden Werte |

### Rückgabewert

true, wenn einer der Werte aus values im Span gefunden wird, sonst false

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion

Prüft, ob ein veränderbarer Span einen beliebigen Wert aus einem schreibgeschützten Span enthält.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente in den Spans |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der veränderbare Span, in dem gesucht wird |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der schreibgeschützte Span der zu suchenden Werte |

### Rückgabewert

true, wenn einer der Werte aus values im Span gefunden wird, sonst false

## Siehe auch

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Namensraum [System::MemoryExtensions](../)
* Bibliothek [Aspose.Slides](../../)