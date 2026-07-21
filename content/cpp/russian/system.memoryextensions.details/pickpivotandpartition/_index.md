---
title: PickPivotAndPartition()
second_title: Aspose.Slides для C++ API Reference
description: Выбирает опорный элемент и разбивает пары ключ-значение для быстрой сортировки.
type: docs
weight: 105
url: /ru/system.memoryextensions.details/pickpivotandpartition/
---
## System::MemoryExtensions::Details::PickPivotAndPartition(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) функция

Выбирает опорный элемент и разбивает пары ключ-значение для быстрой сортировки.

```cpp
template<typename TKey,typename TValue> int32_t System::MemoryExtensions::Details::PickPivotAndPartition(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TKey | Тип ключей |
| TValue | Тип значений |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Диапазон ключей для разделения |
| values | [Span](../../system/span/)\<TValue\>\& | Диапазон значений для разделения |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) функция для ключей |

### Возвращаемое значение

Индекс опорного элемента после разделения

## См. также

* Класс [Span](../../system/span/)
* Пространство имён [System::MemoryExtensions::Details](../)
* Библиотека [Aspose.Slides](../../)