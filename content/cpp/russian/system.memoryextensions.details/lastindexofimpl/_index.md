---
title: LastIndexOfImpl()
second_title: Aspose.Slides для C++ справочник API
description: Находит последний индекс значения в спане.
type: docs
weight: 14
url: /ru/system.memoryextensions.details/lastindexofimpl/
---
## System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan\<T\>\&, int32_t, const T\&) функция


Находит последний индекс значения в спане.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan<T> &searchSpace, int32_t length, const T &value)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в спане |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| searchSpace | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [Span](../../system/span/) для поиска |
| length | **int32_t** | Длина для поиска |
| value | const T\& | Значение для поиска |

### Возвращаемое значение

Последний индекс значения, или -1, если не найдено

## См. также

* Класс [ReadOnlySpan](../../system/readonlyspan/)
* Пространство имён [System::MemoryExtensions::Details](../)
* Библиотека [Aspose.Slides](../../)