---
title: Interlocked
second_title: Справочник API Aspose.Slides для C++
description: Предоставляет API для потокобезопасных операций. Это статический тип без сервисов экземпляра. Вы никогда не должны создавать его экземпляры каким-либо способом.
type: docs
weight: 131
url: /ru/system.threading/interlocked/
---
## Класс Interlocked

Provides API for thread-safe operations. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Interlocked
```

## Методы

| Метод | Описание |
| --- | --- |
| static **int32_t** [Add](./add/)(**int32_t**\&, **int32_t**) | Увеличивает значение атомарно. |
| static **int64_t** [Add](./add/)(**int64_t**\&, **int64_t**) | Увеличивает значение атомарно. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | Сравнивает и меняет значение переменной: проверяет, равно ли переменная определённому значению, и сохраняет новое значение только если текущее значение соответствует ожидаемому. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | Сравнивает и меняет значение переменной: проверяет, равно ли переменная определённому значению, и сохраняет новое значение только если текущее значение соответствует ожидаемому. Не реализовано. |
| static **int32_t** [CompareExchange](./compareexchange/)(**int32_t**\&, **int32_t**, **int32_t**, **bool**\&) | Сравнивает и меняет значение переменной: проверяет, равно ли переменная определённому значению, и сохраняет новое значение только если текущее значение соответствует ожидаемому. |
| static **int32_t** [Decrement](./decrement/)(**int32_t**\&) | Уменьшает значение атомарно. |
| static **int64_t** [Decrement](./decrement/)(**int64_t**\&) | Уменьшает значение атомарно. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | Обменивает значение переменной: сохраняет новое значение и возвращает предыдущее значение переменной сразу же до сохранения. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | Обменивает значение переменной: сохраняет новое значение и возвращает предыдущее значение переменной сразу же до сохранения. Не реализовано. |
| static **int32_t** [ExchangeAdd](./exchangeadd/)(**int32_t**\&, **int32_t**) | Увеличивает значение атомарно с помощью процедуры exchange-add. |
| static **int64_t** [ExchangeAdd](./exchangeadd/)(**int64_t**\&, **int64_t**) | Увеличивает значение атомарно с помощью процедуры exchange-add. |
| static **int32_t** [Increment](./increment/)(**int32_t**\&) | Увеличивает значение атомарно. |
| static **int64_t** [Increment](./increment/)(**int64_t**\&) | Увеличивает значение атомарно. |
| static **int64_t** [Read](./read/)(**int64_t**\&) | Возвращает 64-битное значение, загруженное атомарно. |

## См. также

* Пространство имён [System::Threading](../)
* Библиотека [Aspose.Slides](../../)