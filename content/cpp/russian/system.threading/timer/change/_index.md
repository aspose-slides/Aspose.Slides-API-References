---
title: Change()
second_title: Aspose.Slides для C++: справочник API
description: Перепланирует или отменяет таймер.
type: docs
weight: 14
url: /ru/system.threading/timer/change/
---
## Timer::Change(int64_t, int64_t) метод


Перепланирует или отменяет таймер.

```cpp
bool System::Threading::Timer::Change(int64_t dueTime, int64_t period)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| dueTime | **int64_t** | [Timeout](../../timeout/) перед следующим вызовом функции обратного вызова, в миллисекундах; отрицательные значения отменяют таймер, даже если он был запланирован. |
| period | **int64_t** | [Timeout](../../timeout/) между последовательными вызовами функции обратного вызова, в миллисекундах; не положительные значения означают, что таймер должен выполниться только один раз. |

## Timer::Change(System::TimeSpan, System::TimeSpan) метод


Перепланирует или отменяет таймер.

```cpp
bool System::Threading::Timer::Change(System::TimeSpan dueTime, System::TimeSpan period)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) перед следующим вызовом функции обратного вызова; отрицательные значения отменяют таймер, даже если он был запланирован. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) между последовательными вызовами функции обратного вызова; не положительные значения означают, что таймер должен выполниться только один раз. |

## См. также

* Класс [Timer](../)
* Класс [TimeSpan](../../../system/timespan/)
* Пространство имён [System::Threading](../../)
* Библиотека [Aspose.Slides](../../../)