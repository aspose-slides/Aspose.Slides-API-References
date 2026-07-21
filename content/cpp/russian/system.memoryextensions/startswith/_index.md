---
title: StartsWith()
second_title: Aspose.Slides для C++ справка по API
description: Проверяет, начинается ли span с указанного значения.
type: docs
weight: 352
url: /ru/system.memoryextensions/startswith/
---
## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const T\&) функция

Проверяет, начинается ли span с указанного значения value.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const T &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | The type of elements in the span |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to check |
| value | const T\& | The value to check for at the beginning of the span |

### Возвращаемое значение

true if the span starts with the value, false otherwise

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) функция

Проверяет, начинается ли span с указанного value span.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | The type of elements in the spans |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to check |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span containing values to check for at the beginning |

### Возвращаемое значение

true if the span starts with the value span, false otherwise

## System::MemoryExtensions::StartsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) функция

Проверяет, начинается ли изменяемый span с указанного только для чтения value span.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | The type of elements in the spans |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The mutable span to check |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The read-only span containing values to check for |

### Возвращаемое значение

true if the span starts with the value span, false otherwise

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) функция

Проверяет, начинается ли только для чтения span с указанного изменяемого value span.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | The type of elements in the spans |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The read-only span to check |
| value | const [Span](../../system/span/)\<T\>\& | The mutable span containing values to check for |

### Возвращаемое значение

true if the span starts with the value span, false otherwise

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) функция

Проверяет, начинается ли character span с указанного value span, используя сравнение строк.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The character span to check |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The character span containing values to check for |
| comparisonType | [StringComparison](../../system/stringcomparison/) | The type of string comparison to perform |

### Возвращаемое значение

true if the span starts with the value span, false otherwise

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<String\>\&, const char16_t *) функция

Проверяет, начинается ли string span с указанного массива символов.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<String> &span, const char16_t *val)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<[String](../../system/string/)\>\& | The string span to check |
| val | const char16_t * | The character array to check for at the beginning |

### Возвращаемое значение

true if the span starts with the character array, false otherwise

## См. также

* Перечисление [StringComparison](../../system/stringcomparison/)
* Класс [ReadOnlySpan](../../system/readonlyspan/)
* Класс [Span](../../system/span/)
* Класс [String](../../system/string/)
* Пространство имён [System::MemoryExtensions](../)
* Библиотека [Aspose.Slides](../../)