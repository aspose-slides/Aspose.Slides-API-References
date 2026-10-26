---
title: LastIndexOfAnyExcept()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Znajduje ostatnie wystąpienie dowolnego elementu z wyjątkiem trzech określonych wartości w obrębie zakresu.
type: docs
weight: 235
url: /pl/system.memoryextensions/lastindexofanyexcept/
---
## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) funkcja


Znajduje ostatnie wystąpienie dowolnego elementu z wyjątkiem trzech określonych wartości w obrębie zakresu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to exclude |
| value1 | const T\& | The second value to exclude |
| value2 | const T\& | The third value to exclude |

### Wartość zwracana

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) funkcja


Znajduje ostatnie wystąpienie dowolnego elementu z wyjątkiem trzech określonych wartości w obrębie modyfikowalnego zakresu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to exclude |
| value1 | const T\& | The second value to exclude |
| value2 | const T\& | The third value to exclude |

### Wartość zwracana

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funkcja


Znajduje ostatnie wystąpienie dowolnego elementu z wyjątkiem dwóch określonych wartości w obrębie zakresu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to exclude |
| value1 | const T\& | The second value to exclude |

### Wartość zwracana

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&) funkcja


Znajduje ostatnie wystąpienie dowolnego elementu z wyjątkiem dwóch określonych wartości w obrębie modyfikowalnego zakresu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value0 | const T\& | The first value to exclude |
| value1 | const T\& | The second value to exclude |

### Wartość zwracana

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) funkcja


Znajduje ostatnie wystąpienie dowolnego elementu z wyjątkiem określonej wartości w obrębie zakresu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value | const T\& | The value to exclude |

### Wartość zwracana

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&) funkcja


Znajduje ostatnie wystąpienie dowolnego elementu z wyjątkiem określonej wartości w obrębie modyfikowalnego zakresu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value | const T\& | The value to exclude |

### Wartość zwracana

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funkcja


Znajduje ostatnie wystąpienie dowolnego elementu z wyjątkiem wartości z sekwencji w obrębie zakresu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence of values to exclude |

### Wartość zwracana

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funkcja


Znajduje ostatnie wystąpienie dowolnego elementu z wyjątkiem wartości z sekwencji w obrębie modyfikowalnego zakresu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence of values to exclude |

### Wartość zwracana

The zero-based index of the last non-excluded element, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const Span\<T\>\&) funkcja


Znajduje ostatnie wystąpienie dowolnego elementu z wyjątkiem wartości z modyfikowalnej sekwencji w obrębie modyfikowalnego zakresu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const Span<T> &values)
```


### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| values | const [Span](../../system/span/)\<T\>\& | The sequence of values to exclude |

### Wartość zwracana

The zero-based index of the last non-excluded element, or -1 if not found

## Zobacz także

* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Klasa [Span](../../system/span/)
* Przestrzeń nazw [System::MemoryExtensions](../)
* Biblioteka [Aspose.Slides](../../)