---
title: IndexOfAnyInRange()
second_title: Aspose.Slides для C++ справочник API
description: Находит индекс первого элемента, который находится в указанном диапазоне в ReadOnlySpan<T>
type: docs
weight: 196
url: /ru/system.memoryextensions/indexofanyinrange/
---
## System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) функция

Finds the index of the first element that is within the specified range in a ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в span |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span для поиска |
| lowInclusive | const T\& | Нижняя граница диапазона (включительно) |
| highInclusive | const T\& | Верхняя граница диапазона (включительно) |

### Возвращаемое значение

Нулевой индекс первого элемента в диапазоне, или -1, если он не найден

## System::MemoryExtensions::IndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) функция

Finds the index of the first element that is within the specified range in a Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в span |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span для поиска |
| lowInclusive | const T\& | Нижняя граница диапазона (включительно) |
| highInclusive | const T\& | Верхняя граница диапазона (включительно) |

### Возвращаемое значение

Нулевой индекс первого элемента в диапазоне, или -1, если он не найден

## См. также

* Класс [ReadOnlySpan](../../system/readonlyspan/)
* Класс [Span](../../system/span/)
* Пространство имён [System::MemoryExtensions](../)
* Библиотека [Aspose.Slides](../../)