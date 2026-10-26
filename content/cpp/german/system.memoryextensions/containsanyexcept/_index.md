---
title: ContainsAnyExcept()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft, ob ein schreibgeschützter Span ein Element enthält, das nicht zu den drei angegebenen Werten gehört.
type: docs
weight: 66
url: /de/system.memoryextensions/containsanyexcept/
---
## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function

Überprüft, ob ein schreibgeschützter Span ein Element enthält, das nicht zu den drei angegebenen Werten gehört.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Vorlagenparameter

| Parameter | Description |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zu durchsuchende Span |
| value0 | const T\& | Der erste auszuschließende Wert |
| value1 | const T\& | Der zweite auszuschließende Wert |
| value2 | const T\& | Der dritte auszuschließende Wert |

### Rückgabewert

true, wenn ein Element, das von den angegebenen Werten abweicht, gefunden wird, sonst false

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) function

Überprüft, ob ein veränderbarer Span ein Element enthält, das nicht zu den drei angegebenen Werten gehört.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Vorlagenparameter

| Parameter | Description |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der zu durchsuchende veränderbare Span |
| value0 | const T\& | Der erste auszuschließende Wert |
| value1 | const T\& | Der zweite auszuschließende Wert |
| value2 | const T\& | Der dritte auszuschließende Wert |

### Rückgabewert

true, wenn ein Element, das von den angegebenen Werten abweicht, gefunden wird, sonst false

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

Überprüft, ob ein schreibgeschützter Span ein Element enthält, das nicht zu den zwei angegebenen Werten gehört.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Vorlagenparameter

| Parameter | Description |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zu durchsuchende Span |
| value0 | const T\& | Der erste auszuschließende Wert |
| value1 | const T\& | Der zweite auszuschließende Wert |

### Rückgabewert

true, wenn ein Element, das von den angegebenen Werten abweicht, gefunden wird, sonst false

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&) function

Überprüft, ob ein veränderbarer Span ein Element enthält, das nicht zu den zwei angegebenen Werten gehört.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### Vorlagenparameter

| Parameter | Description |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der zu durchsuchende veränderbare Span |
| value0 | const T\& | Der erste auszuschließende Wert |
| value1 | const T\& | Der zweite auszuschließende Wert |

### Rückgabewert

true, wenn ein Element, das von den angegebenen Werten abweicht, gefunden wird, sonst false

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) function

Überprüft, ob ein schreibgeschützter Span ein Element enthält, das nicht dem angegebenen Wert entspricht.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### Vorlagenparameter

| Parameter | Description |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zu durchsuchende Span |
| value | const T\& | Der auszuschließende Wert |

### Rückgabewert

true, wenn ein Element, das von dem angegebenen Wert abweicht, gefunden wird, sonst false

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&) function

Überprüft, ob ein veränderbarer Span ein Element enthält, das nicht dem angegebenen Wert entspricht.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value)
```

### Vorlagenparameter

| Parameter | Description |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der zu durchsuchende veränderbare Span |
| value | const T\& | Der auszuschließende Wert |

### Rückgabewert

true, wenn ein Element, das von dem angegebenen Wert abweicht, gefunden wird, sonst false

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Überprüft, ob ein schreibgeschützter Span ein Element enthält, das nicht in einem anderen Span vorkommt.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Vorlagenparameter

| Parameter | Description |
| --- | --- |
| T | Der Typ der Elemente in den Spans |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zu durchsuchende Span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der Span der auszuschließenden Werte |

### Rückgabewert

true, wenn ein Element, das nicht in values ist, gefunden wird, sonst false

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Überprüft, ob ein veränderbarer Span ein Element enthält, das nicht in einem schreibgeschützten Span vorkommt.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Vorlagenparameter

| Parameter | Description |
| --- | --- |
| T | Der Typ der Elemente in den Spans |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der zu durchsuchende veränderbare Span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der schreibgeschützte Span der auszuschließenden Werte |

### Rückgabewert

true, wenn ein Element, das nicht in values ist, gefunden wird, sonst false

## Siehe auch

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Namensraum [System::MemoryExtensions](../)
* Bibliothek [Aspose.Slides](../../)