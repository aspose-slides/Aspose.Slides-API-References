---
title: WaitOne()
second_title: Справочник API Aspose.Slides для C++
description: Блокирует семафор. Выполняет неограниченное ожидание при необходимости.
type: docs
weight: 40
url: /ru/system.threading/semaphore/waitone/
---
## Semaphore::WaitOne() метод

Блокирует семафор. Выполняет неограниченное ожидание при необходимости.

```cpp
virtual bool System::Threading::Semaphore::WaitOne() override
```

### Возвращаемое значение

Всегда возвращает true, так как не возвращается, пока семафор не будет заблокирован.

## Semaphore::WaitOne(int) метод

Блокирует семафор. Выполняет ожидание при необходимости.

```cpp
virtual bool System::Threading::Semaphore::WaitOne(int millisecondsTimeout) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| millisecondsTimeout | int | Время ожидания в миллисекундах. |

### Возвращаемое значение

Возвращает true, если семафор был заблокирован, или false, если время ожидания истекло.

## См. также

* Класс [Semaphore](../)
* Пространство имён [System::Threading](../../)
* Библиотека [Aspose.Slides](../../../)