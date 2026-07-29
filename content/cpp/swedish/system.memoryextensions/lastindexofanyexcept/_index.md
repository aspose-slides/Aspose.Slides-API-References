---
title: LastIndexOfAnyExcept()
second_title: Aspose.Slides för C++ API-referens
description: Söker den sista förekomsten av ett element förutom tre angivna värden inom ett span.
type: docs
weight: 235
url: /sv/system.memoryextensions/lastindexofanyexcept/
---
## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function

Söker den sista förekomsten av ett element förutom tre angivna värden inom ett span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Mallparametrar

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to exclude |
| value1 | const T\& | The second value to exclude |
| value2 | const T\& | The third value to exclude |

### Returvärde

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) function

Söker den sista förekomsten av ett element förutom tre angivna värden inom ett modifierbart span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Mallparametrar

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to exclude |
| value1 | const T\& | The second value to exclude |
| value2 | const T\& | The third value to exclude |

### Returvärde

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

Söker den sista förekomsten av ett element förutom två angivna värden inom ett span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Mallparametrar

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to exclude |
| value1 | const T\& | The second value to exclude |

### Returvärde

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&) function

Söker den sista förekomsten av ett element förutom två angivna värden inom ett modifierbart span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### Mallparametrar

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to exclude |
| value1 | const T\& | The second value to exclude |

### Returvärde

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) function

Söker den sista förekomsten av ett element förutom ett specificerat värde inom ett span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### Mallparametrar

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value | const T\& | The value to exclude |

### Returvärde

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&) function

Söker den sista förekomsten av ett element förutom ett specificerat värde inom ett modifierbart span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value)
```

### Mallparametrar

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value | const T\& | The value to exclude |

### Returvärde

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Söker den sista förekomsten av ett element förutom värden från en sekvens inom ett span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Mallparametrar

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence of values to exclude |

### Returvärde

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Söker den sista förekomsten av ett element förutom värden från en sekvens inom ett modifierbart span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Mallparametrar

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence of values to exclude |

### Returvärde

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const Span\<T\>\&) function

Söker den sista förekomsten av ett element förutom värden från en modifierbar sekvens inom ett modifierbart span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const Span<T> &values)
```

### Mallparametrar

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| values | const [Span](../../system/span/)\<T\>\& | The sequence of values to exclude |

### Returvärde

The zero-based index of the last non-excluded element, or -1 if not found

## Se även

* Klass [ReadOnlySpan](../../system/readonlyspan/)
* Klass [Span](../../system/span/)
* Namnrymd [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)