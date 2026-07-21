---
title: IndexOfAnyExceptInRange()
second_title: Aspose.Slides для C++ API справка
description: Находит индекс первого элемента, который находится за пределами указанного диапазона в ReadOnlySpan<T>
type: docs
weight: 183
url: /ru/system.memoryextensions/indexofanyexceptinrange/
---
## System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) функция

Находит индекс первого элемента, который находится за пределами указанного диапазона в ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в спане |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Спан, в котором осуществляется поиск |
| lowInclusive | const T\& | Нижняя граница диапазона (включительно) |
| highInclusive | const T\& | Верхняя граница диапазона (включительно) |

### Возвращаемое значение

Нулевой индекс первого элемента, находящегося за пределами диапазона, или -1, если не найден

## System::MemoryExtensions::IndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) функция

Находит индекс первого элемента, который находится за пределами указанного диапазона в Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в спане |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Спан, в котором осуществляется поиск |
| lowInclusive | const T\& | Нижняя граница диапазона (включительно) |
| highInclusive | const T\& | Верхняя граница диапазона (включительно) |

### Возвращаемое значение

Нулевой индекс первого элемента, находящегося за пределами диапазона, или -1, если не найден

## См. также

* Класс [ReadOnlySpan](../../system/readonlyspan/)
* Класс [Span](../../system/span/)
* Пространство имён [System::MemoryExtensions](../)
* Библиотека [Aspose.Slides](../../)