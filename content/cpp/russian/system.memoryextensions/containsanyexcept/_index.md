---
title: ContainsAnyExcept()
second_title: Aspose.Slides для C++ – справочник API
description: Проверяет, содержит ли только для чтения span какой-либо элемент, отличный от трёх указанных значений.
type: docs
weight: 66
url: /ru/system.memoryextensions/containsanyexcept/
---
## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function

Проверяет, содержит ли только для чтения span какой-либо элемент, отличный от трёх указанных значений.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | The type of elements in the span |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value0 | const T\& | The first value to exclude |
| value1 | const T\& | The second value to exclude |
| value2 | const T\& | The third value to exclude |

### Возвращаемое значение

true, если найден любой элемент, отличный от указанных значений; false в противном случае

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) function

Проверяет, содержит ли изменяемый span какой-либо элемент, отличный от трёх указанных значений.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | The type of elements in the span |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The mutable span to search in |
| value0 | const T\& | The first value to exclude |
| value1 | const T\& | The second value to exclude |
| value2 | const T\& | The third value to exclude |

### Возвращаемое значение

true, если найден любой элемент, отличный от указанных значений; false в противном случае

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

Проверяет, содержит ли только для чтения span какой-либо элемент, отличный от двух указанных значений.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | The type of elements in the span |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value0 | const T\& | The first value to exclude |
| value1 | const T\& | The second value to exclude |

### Возвращаемое значение

true, если найден любой элемент, отличный от указанных значений; false в противном случае

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&) function

Проверяет, содержит ли изменяемый span какой-либо элемент, отличный от двух указанных значений.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | The type of elements in the span |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The mutable span to search in |
| value0 | const T\& | The first value to exclude |
| value1 | const T\& | The second value to exclude |

### Возвращаемое значение

true, если найден любой элемент, отличный от указанных значений; false в противном случае

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) function

Проверяет, содержит ли только для чтения span какой-либо элемент, отличный от указанного значения.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | The type of elements in the span |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value | const T\& | The value to exclude |

### Возвращаемое значение

true, если найден любой элемент, отличный от указанного значения; false в противном случае

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&) function

Проверяет, содержит ли изменяемый span какой-либо элемент, отличный от указанного значения.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | The type of elements in the span |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The mutable span to search in |
| value | const T\& | The value to exclude |

### Возвращаемое значение

true, если найден любой элемент, отличный от указанного значения; false в противном случае

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Проверяет, содержит ли только для чтения span какой-либо элемент, отличный от элементов в другом span.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | The type of elements in the spans |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span of values to exclude |

### Возвращаемое значение

true, если найден любой элемент, не входящий в values; false в противном случае

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Проверяет, содержит ли изменяемый span какой-либо элемент, отличный от элементов в только для чтения span.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | The type of elements in the spans |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The mutable span to search in |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The read-only span of values to exclude |

### Возвращаемое значение

true, если найден любой элемент, не входящий в values; false в противном случае

## См. также

* Класс [ReadOnlySpan](../../system/readonlyspan/)
* Класс [Span](../../system/span/)
* Пространство имён [System::MemoryExtensions](../)
* Библиотека [Aspose.Slides](../../)