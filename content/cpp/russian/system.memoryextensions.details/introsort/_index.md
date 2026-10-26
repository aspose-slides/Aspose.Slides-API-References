---
title: IntroSort()
second_title: Aspose.Slides для C++ справочник API
description: Внутренняя реализация алгоритма introsort для пар ключ-значение.
type: docs
weight: 40
url: /ru/system.memoryextensions.details/introsort/
---
## System::MemoryExtensions::Details::IntroSort(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) функция

Внутренняя реализация алгоритма introsort для пар ключ-значение.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::IntroSort(Span<TKey> &keys, Span<TValue> &values, int32_t depthLimit, std::function<int32_t(const TKey &, const TKey &)> comparer)
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
| depthLimit | **int32_t** | Максимальная глубина рекурсии до перехода к heapsort |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) функция для ключей |

## См. также

* Класс [Span](../../system/span/)
* Пространство имён [System::MemoryExtensions::Details](../)
* Библиотека [Aspose.Slides](../../)