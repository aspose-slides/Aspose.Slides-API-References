---
title: LastIndexOfAnyExceptInRange()
second_title: Справочник API Aspose.Slides для C++
description: Находит последнее вхождение любого элемента за пределами указанного диапазона в спане.
type: docs
weight: 248
url: /ru/system.memoryextensions/lastindexofanyexceptinrange/
---
## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) функция

Находит последнее вхождение любого элемента за пределами указанного диапазона в спане.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | Тип элементов в спане |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Спан, в котором выполняется поиск |
| lowInclusive | const T\& | Нижняя граница диапазона (включительно) |
| highInclusive | const T\& | Верхняя граница диапазона (включительно) |

### Возвращаемое значение

Нулевой индекс последнего элемента за пределами диапазона, или -1 если не найден

## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) функция

Находит последнее вхождение любого элемента за пределами указанного диапазона в изменяемом спане.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | Тип элементов в спане |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Спан, в котором выполняется поиск |
| lowInclusive | const T\& | Нижняя граница диапазона (включительно) |
| highInclusive | const T\& | Верхняя граница диапазона (включительно) |

### Возвращаемое значение

Нулевой индекс последнего элемента за пределами диапазона, или -1 если не найден

## См. также

* Класс [ReadOnlySpan](../../system/readonlyspan/)
* Класс [Span](../../system/span/)
* Пространство имён [System::MemoryExtensions](../)
* Библиотека [Aspose.Slides](../../)