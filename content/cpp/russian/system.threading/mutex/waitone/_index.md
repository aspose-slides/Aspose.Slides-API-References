---
title: WaitOne()
second_title: Aspose.Slides для C++ справочник API
description: Блокирует мьютекс. Выполняет неограниченное ожидание, если необходимо.
type: docs
weight: 53
url: /ru/system.threading/mutex/waitone/
---
## Mutex::WaitOne() метод


Блокирует мьютекс. Выполняет неограниченное ожидание, если необходимо.

```cpp
virtual bool System::Threading::Mutex::WaitOne() override
```


### Возвращаемое значение

Всегда возвращает true, так как не возвращает управление, пока мьютекс не будет заблокирован.

## Mutex::WaitOne(int) метод


Блокирует мьютекс. Выполняет ожидание, если необходимо.

```cpp
virtual bool System::Threading::Mutex::WaitOne(int millisecondsTimeout) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| millisecondsTimeout | int | Время ожидания в миллисекундах. |

### Возвращаемое значение

Возвращает true, если мьютекс был заблокирован, или false, если время ожидания превысило предел.

## Mutex::WaitOne(TimeSpan) метод


Блокирует мьютекс. Выполняет ожидание, если необходимо.

```cpp
virtual bool System::Threading::Mutex::WaitOne(TimeSpan timeout) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/), представляющий количество миллисекунд для ожидания, или [System::TimeSpan](../../../system/timespan/), представляющий -1 миллисекунду для бесконечного ожидания. |

### Возвращаемое значение

Возвращает true, если мьютекс был заблокирован, или false, если время ожидания превысило предел.

## См. также

* Класс [Mutex](../)
* Класс [TimeSpan](../../../system/timespan/)
* Пространство имён [System::Threading](../../)
* Библиотека [Aspose.Slides](../../../)