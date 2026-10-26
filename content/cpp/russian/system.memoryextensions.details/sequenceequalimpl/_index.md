---
title: SequenceEqualImpl()
second_title: Aspose.Slides для C++ справка по API
description: Проверяет, равны ли два спана, начиная с указанных позиций.
type: docs
weight: 27
url: /ru/system.memoryextensions.details/sequenceequalimpl/
---
## System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan\<T\>\&, const int32_t, int32_t, const ReadOnlySpan\<T\>\&) функция

Проверяет, равны ли два спана, начиная с указанных позиций.

```cpp
template<typename T> bool System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan<T> &first, const int32_t start, int32_t length, const ReadOnlySpan<T> &second)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в спанах |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Первый спан |
| start | const **int32_t** | Начальный индекс в первом спане |
| length | **int32_t** | Количество элементов для сравнения |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Второй спан |

### Возвращаемое значение

true если указанные диапазоны равны, false иначе

## См. также

* Класс [ReadOnlySpan](../../system/readonlyspan/)
* Пространство имён [System::MemoryExtensions::Details](../)
* Библиотека [Aspose.Slides](../../)