---
title: IndexOf()
second_title: Aspose.Slides для C++ справочник API
description: Находит индекс значения ReadOnlySpan<T> в другом ReadOnlySpan<T>
type: docs
weight: 144
url: /ru/system.memoryextensions/indexof/
---
## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Находит индекс значения ReadOnlySpan<T> в другом ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в диапазонах |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Диапазон, в котором выполняется поиск |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Диапазон, который нужно найти |

### Возвращаемое значение

Нулевой индекс первого вхождения, или -1, если не найдено

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const T\&) function

Находит индекс одиночного значения в ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const T &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в диапазоне |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Диапазон, в котором выполняется поиск |
| value | const T\& | Значение, которое нужно найти |

### Возвращаемое значение

Нулевой индекс первого вхождения, или -1, если не найдено

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Находит индекс значения ReadOnlySpan<T> в Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в диапазонах |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Диапазон, в котором выполняется поиск |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Диапазон, который нужно найти |

### Возвращаемое значение

Нулевой индекс первого вхождения, или -1, если не найдено

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const T\&) function

Находит индекс одиночного значения в Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const T &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в диапазоне |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Диапазон, в котором выполняется поиск |
| value | const T\& | Значение, которое нужно найти |

### Возвращаемое значение

Нулевой индекс первого вхождения, или -1, если не найдено

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function

Находит индекс значения ReadOnlySpan<char16_t> в ReadOnlySpan<char16_t> с использованием StringComparison.

```cpp
int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Диапазон, в котором выполняется поиск |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Значение, которое нужно найти |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Тип сравнения строк, который следует использовать |

### Возвращаемое значение

Нулевой индекс первого вхождения, или -1, если не найдено

## См. также

* Перечисление [StringComparison](../../system/stringcomparison/)
* Класс [ReadOnlySpan](../../system/readonlyspan/)
* Класс [Span](../../system/span/)
* Пространство имён [System::MemoryExtensions](../)
* Библиотека [Aspose.Slides](../../)