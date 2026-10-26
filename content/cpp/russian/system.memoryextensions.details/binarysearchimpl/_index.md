---
title: BinarySearchImpl()
second_title: Справочник API Aspose.Slides для C++
description: Общая реализация двоичного поиска.
type: docs
weight: 118
url: /ru/system.memoryextensions.details/binarysearchimpl/
---
## System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan\<T\>\&, const TValue\&, TCompareFunc) функция


Общая реализация двоичного поиска.

```cpp
template<typename T,typename TValue,typename TCompareFunc> int32_t System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan<T> &span, const TValue &value, TCompareFunc compareFunc)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в span |
| TValue | Тип значения для поиска |
| TCompareFunc | Тип функции для сравнения |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span для поиска |
| value | const TValue\& | Значение для поиска |
| compareFunc | TCompareFunc | Функция, сравнивающая value со элементом span и возвращающая **int32_t** (-1, 0, 1) |

### Возвращаемое значение

Индекс найденного элемента или побитовое дополнение точки вставки

## См. также

* Класс [ReadOnlySpan](../../system/readonlyspan/)
* Пространство имён [System::MemoryExtensions::Details](../)
* Библиотека [Aspose.Slides](../../)