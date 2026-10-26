---
title: Heapify()
second_title: Aspose.Slides для C++ API Reference
description: Поддерживает свойство кучи для пар ключ-значение.
type: docs
weight: 92
url: /ru/system.memoryextensions.details/heapify/
---
## System::MemoryExtensions::Details::Heapify(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) функция

Поддерживает свойство кучи для пар ключ-значение.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::Heapify(Span<TKey> &keys, Span<TValue> &values, int32_t n, int32_t i, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TKey | Тип ключей |
| TValue | Тип значений |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Диапазон ключей в куче |
| values | [Span](../../system/span/)\<TValue\>\& | Диапазон значений в куче |
| n | **int32_t** | Размер кучи |
| i | **int32_t** | Индекс, с которого выполнять heapify |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) функция для ключей |

## См. также

* Класс [Span](../../system/span/)
* Пространство имён [System::MemoryExtensions::Details](../)
* Библиотека [Aspose.Slides](../../)