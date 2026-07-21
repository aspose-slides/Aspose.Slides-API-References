---
title: Overlaps()
second_title: Aspose.Slides для C++ справочник API
description: Определяет, пересекаются ли два ReadOnlySpans в памяти без вычисления смещения.
type: docs
weight: 274
url: /ru/system.memoryextensions/overlaps/
---
## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Определяет, пересекаются ли два ReadOnlySpan в памяти без вычисления смещения.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в диапазонах |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Первый диапазон для проверки пересечения |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Второй диапазон для проверки пересечения |

### Возвращаемое значение

true, если диапазоны делят любые общие области памяти, false в противном случае

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Определяет, пересекаются ли [Span](../../system/span/) и [ReadOnlySpan](../../system/readonlyspan/) в памяти без вычисления смещения.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в диапазонах |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) для проверки пересечения |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) для проверки пересечения |

### Возвращаемое значение

true, если диапазоны делят любые общие области памяти, false в противном случае

## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) function

Определяет, пересекаются ли два ReadOnlySpan в памяти и вычисляет смещение.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в диапазонах |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Первый диапазон для проверки пересечения |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Второй диапазон для проверки пересечения |
| elementOffset | **int32_t**\& | Выходной параметр, получающий смещение между диапазонами при их пересечении |

### Возвращаемое значение

true, если диапазоны делят любые общие области памяти, false в противном случае

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) function

Определяет, пересекаются ли [Span](../../system/span/) и [ReadOnlySpan](../../system/readonlyspan/) в памяти и вычисляет смещение.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в диапазонах |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) для проверки пересечения |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) для проверки пересечения |
| elementOffset | **int32_t**\& | Выходной параметр, получающий смещение между диапазонами при их пересечении |

### Возвращаемое значение

true, если диапазоны делят любые общие области памяти, false в противном случае

## См. также

* Класс [ReadOnlySpan](../../system/readonlyspan/)
* Класс [Span](../../system/span/)
* Пространство имён [System::MemoryExtensions](../)
* Библиотека [Aspose.Slides](../../)