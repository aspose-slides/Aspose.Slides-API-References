---
title: SequenceCompareTo()
second_title: Aspose.Slides для C++: справочник API
description: Сравнивает два ReadOnlySpans лексикографически.
type: docs
weight: 313
url: /ru/system.memoryextensions/sequencecompareto/
---
## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) функция

Сравнивает два ReadOnlySpan лексикографически.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в spanах |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Первый span для сравнения |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Второй span для сравнения |

### Возвращаемое значение

- 1 если span < other, 0 если span == other, 1 если span > other

## System::MemoryExtensions::SequenceCompareTo(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) функция

Сравнивает [Span](../../system/span/) и [ReadOnlySpan](../../system/readonlyspan/) лексикографически.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в spanах |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) для сравнения |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) для сравнения |

### Возвращаемое значение

- 1 если span < other, 0 если span == other, 1 если span > other

## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) функция

Сравнивает [ReadOnlySpan](../../system/readonlyspan/) и [Span](../../system/span/) лексикографически.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const Span<T> &other)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в spanах |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) для сравнения |
| other | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) для сравнения |

### Возвращаемое значение

- 1 если span < other, 0 если span == other, 1 если span > other

## См. также

* Класс [ReadOnlySpan](../../system/readonlyspan/)
* Класс [Span](../../system/span/)
* Пространство имён [System::MemoryExtensions](../)
* Библиотека [Aspose.Slides](../../)