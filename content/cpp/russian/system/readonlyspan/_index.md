---
title: ReadOnlySpan
second_title: Справочник API Aspose.Slides для C++
description: Перенаправление для использования внутри класса Span.
type: docs
weight: 1184
url: /ru/system/readonlyspan/
---
## ReadOnlySpan класс

Перенаправление для использования внутри класса [Span](../span/).

```cpp
template<typename T>class ReadOnlySpan : public System::Details::SpanCore<const T, ReadOnlySpan<T>, Span<T>>
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в span. Этот класс предоставляет типобезопасный способ работы с непрерывными последовательностями объектов только для чтения. Он может использоваться для обертывания массивов, стековых массивов или сырых указателей с сохранением проверки границ. [ReadOnlySpan](./) не владеет памятью, на которую указывает — это лишь представление существующей памяти. |

## Методы

| Метод | Описание |
| --- | --- |
| [ReadOnlySpan](./readonlyspan/)(const [Span](../span/)\<T\>\&) | Создаёт только для чтения span из обычного span. |
| static [ThisType](./) [to_ReadOnlySpan](./to_readonlyspan/)(const typename BaseType::ArrayPtrT\&) | Преобразует массив в [ReadOnlySpan](./). |

## Замечания

Представляет только для чтения непрерывный регион произвольной памяти.

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)