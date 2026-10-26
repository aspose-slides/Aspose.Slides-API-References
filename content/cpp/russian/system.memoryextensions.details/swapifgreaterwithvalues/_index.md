---
title: SwapIfGreaterWithValues()
second_title: Aspose.Slides для C++ API Reference
description: Меняет местами пары ключ-значение, если условие сравнения выполнено.
type: docs
weight: 53
url: /ru/system.memoryextensions.details/swapifgreaterwithvalues/
---
## System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>, int32_t, int32_t) function

Меняет местами пары ключ-значение, если условие сравнения выполнено.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer, int32_t i, int32_t j)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TKey | Тип ключей |
| TValue | Тип значений |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Диапазон ключей |
| values | [Span](../../system/span/)\<TValue\>\& | Диапазон значений |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) функция для ключей |
| i | **int32_t** | Первый индекс для сравнения |
| j | **int32_t** | Второй индекс для сравнения |

## См. также

* Класс [Span](../../system/span/)
* Пространство имён [System::MemoryExtensions::Details](../)
* Библиотека [Aspose.Slides](../../)