---
title: LastIndexOfAnyInRange()
second_title: Aspose.Slides для C++ API Справка
description: Находит последнее вхождение любого элемента в указанном диапазоне внутри спана.
type: docs
weight: 261
url: /ru/system.memoryextensions/lastindexofanyinrange/
---
## System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) функция


Находит последнее вхождение любого элемента в указанном диапазоне внутри спана.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в спане |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Спан, в котором выполняется поиск |
| lowInclusive | const T\& | Нижняя граница диапазона (включительно) |
| highInclusive | const T\& | Верхняя граница диапазона (включительно) |

### Возвращаемое значение

Нулевой индекс последнего элемента в диапазоне, или -1, если элемент не найден

## System::MemoryExtensions::LastIndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) функция


Находит последнее вхождение любого элемента в указанном диапазоне внутри изменяемого спана.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в спане |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Спан, в котором выполняется поиск |
| lowInclusive | const T\& | Нижняя граница диапазона (включительно) |
| highInclusive | const T\& | Верхняя граница диапазона (включительно) |

### Возвращаемое значение

Нулевой индекс последнего элемента в диапазоне, или -1, если элемент не найден

## См. также

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)