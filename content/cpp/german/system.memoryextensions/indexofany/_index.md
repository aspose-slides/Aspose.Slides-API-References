---
title: IndexOfAny()
second_title: Aspose.Slides für C++ API-Referenz
description: Findet den Index des ersten Auftretens eines der beiden angegebenen Werte in einem ReadOnlySpan<T>
type: docs
weight: 157
url: /de/system.memoryextensions/indexofany/
---
## System::MemoryExtensions::IndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) Funktion

Findet den Index des ersten Auftretens eines beliebigen der zwei angegebenen Werte in einem ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der span, in dem gesucht wird |
| value0 | const T\& | Der erste Wert, nach dem gesucht wird |
| value1 | const T\& | Der zweite Wert, nach dem gesucht wird |

### Rückgabewert

Der nullbasierte Index des ersten Auftretens oder -1, wenn nicht gefunden

## System::MemoryExtensions::IndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) Funktion

Findet den Index des ersten Auftretens eines beliebigen der drei angegebenen Werte in einem ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der span, in dem gesucht wird |
| value0 | const T\& | Der erste Wert, nach dem gesucht wird |
| value1 | const T\& | Der zweite Wert, nach dem gesucht wird |
| value2 | const T\& | Der dritte Wert, nach dem gesucht wird |

### Rückgabewert

Der nullbasierte Index des ersten Auftretens oder -1, wenn nicht gefunden

## System::MemoryExtensions::IndexOfAny(const Span\<T\>\&, const T\&, const T\&) Funktion

Findet den Index des ersten Auftretens eines beliebigen der zwei angegebenen Werte in einem Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der span, in dem gesucht wird |
| value0 | const T\& | Der erste Wert, nach dem gesucht wird |
| value1 | const T\& | Der zweite Wert, nach dem gesucht wird |

### Rückgabewert

Der nullbasierte Index des ersten Auftretens oder -1, wenn nicht gefunden

## System::MemoryExtensions::IndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) Funktion

Findet den Index des ersten Auftretens eines beliebigen der drei angegebenen Werte in einem Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der span, in dem gesucht wird |
| value0 | const T\& | Der erste Wert, nach dem gesucht wird |
| value1 | const T\& | Der zweite Wert, nach dem gesucht wird |
| value2 | const T\& | Der dritte Wert, nach dem gesucht wird |

### Rückgabewert

Der nullbasierte Index des ersten Auftretens oder -1, wenn nicht gefunden

## System::MemoryExtensions::IndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion

Findet den Index des ersten Auftretens eines beliebigen Werts aus einem span in einem anderen ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente in den spans |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der span, in dem gesucht wird |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der span, der die zu suchenden Werte enthält |

### Rückgabewert

Der nullbasierte Index des ersten Auftretens oder -1, wenn nicht gefunden

## System::MemoryExtensions::IndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion

Findet den Index des ersten Auftretens eines beliebigen Werts aus einem span in einem Span<T)

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente in den spans |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der span, in dem gesucht wird |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der span, der die zu suchenden Werte enthält |

### Rückgabewert

Der nullbasierte Index des ersten Auftretens oder -1, wenn nicht gefunden

## Siehe auch

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Namensraum [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)