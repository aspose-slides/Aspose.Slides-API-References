---
title: HeapSort()
second_title: Aspose.Slides для C++ справочник API
description: Выполняет пирамидальную сортировку пар ключ-значение.
type: docs
weight: 79
url: /ru/system.memoryextensions.details/heapsort/
---
## System::MemoryExtensions::Details::HeapSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) функция

Выполняет пирамидальную сортировку пар ключ-значение.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::HeapSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TKey | Тип ключей |
| TValue | Тип значений |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Диапазон ключей для сортировки |
| values | [Span](../../system/span/)\<TValue\>\& | Диапазон значений для сортировки |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) функция для ключей |

## См. также

* Класс [Span](../../system/span/)
* Пространство имен [System::MemoryExtensions::Details](../)
* Библиотека [Aspose.Slides](../../)