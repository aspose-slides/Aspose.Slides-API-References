---
title: LastIndexOf()
second_title: Справочник API Aspose.Slides для C++
description: Находит последнее вхождение последовательности в span.
type: docs
weight: 209
url: /ru/system.memoryextensions/lastindexof/
---
## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


Находит последнее вхождение последовательности в span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence to search for |

### Возвращаемое значение

The zero-based index of the last occurrence, or -1 if not found

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const T\&) function


Находит последнее вхождение отдельного значения в span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const T &value)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value | const T\& | The value to search for |

### Возвращаемое значение

The zero-based index of the last occurrence, or -1 if not found

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


Находит последнее вхождение последовательности в изменяемый span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence to search for |

### Возвращаемое значение

The zero-based index of the last occurrence, or -1 if not found

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const T\&) function


Находит последнее вхождение отдельного значения в изменяемый span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const T &value)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value | const T\& | The value to search for |

### Возвращаемое значение

The zero-based index of the last occurrence, or -1 if not found

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function


Находит последнее вхождение значения в span с использованием указанного сравнения строк.

```cpp
int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The span to search within |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The value to search for |
| comparisonType | [StringComparison](../../system/stringcomparison/) | The type of string comparison to perform |

### Возвращаемое значение

The zero-based index of the last occurrence, or -1 if not found

## См. также

* Перечисление [StringComparison](../../system/stringcomparison/)
* Класс [ReadOnlySpan](../../system/readonlyspan/)
* Класс [Span](../../system/span/)
* Пространство имён [System::MemoryExtensions](../)
* Библиотека [Aspose.Slides](../../)