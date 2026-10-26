---
title: InsertionSort()
second_title: Aspose.Slides для C++ справка API
description: Выполняет сортировку вставкой пар ключ-значение.
type: docs
weight: 66
url: /ru/system.memoryextensions.details/insertionsort/
---
## System::MemoryExtensions::Details::InsertionSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) функция


Выполняет сортировку вставкой пар ключ-значение.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::InsertionSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TKey | Тип ключей |
| TValue | Тип значений |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Спан ключей для сортировки |
| values | [Span](../../system/span/)\<TValue\>\& | Спан значений для сортировки |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) функция для ключей |

## См. также

* Класс [Span](../../system/span/)
* Пространство имён [System::MemoryExtensions::Details](../)
* Библиотека [Aspose.Slides](../../)