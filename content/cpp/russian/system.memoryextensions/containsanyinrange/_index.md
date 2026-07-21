---
title: ContainsAnyInRange()
second_title: Справочник API Aspose.Slides для C++
description: Проверяет, содержит ли только-для-чтения span любой элемент в указанном диапазоне.
type: docs
weight: 92
url: /ru/system.memoryextensions/containsanyinrange/
---
## System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) функция


Проверяет, содержит ли только-для-чтения span любой элемент в указанном диапазоне.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | Тип элементов в span (должен быть сравнимым) |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, в котором производится поиск |
| lowInclusive | const T\& | Нижняя граница (включительно) |
| highInclusive | const T\& | Верхняя граница (включительно) |

### Возвращаемое значение

true, если найден любой элемент в диапазоне, иначе false

## System::MemoryExtensions::ContainsAnyInRange(const Span\<T\>\&, const T\&, const T\&) функция


Проверяет, содержит ли изменяемый span любой элемент в указанном диапазоне.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | Тип элементов в span (должен быть сравнимым) |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Изменяемый span, в котором проводится поиск |
| lowInclusive | const T\& | Нижняя граница (включительно) |
| highInclusive | const T\& | Верхняя граница (включительно) |

### Возвращаемое значение

true, если найден любой элемент в диапазоне, иначе false

## См. также

* Класс [ReadOnlySpan](../../system/readonlyspan/)
* Класс [Span](../../system/span/)
* Пространство имён [System::MemoryExtensions](../)
* Библиотека [Aspose.Slides](../../)