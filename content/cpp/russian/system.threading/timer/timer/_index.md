---
title: Timer()
second_title: Справочная документация API Aspose.Slides для C++
description: Конструктор.
type: docs
weight: 1
url: /ru/system.threading/timer/timer/
---
## Timer::Timer(TimerCallback) конструктор

Конструктор.

```cpp
System::Threading::Timer::Timer(TimerCallback callback)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Функция, вызываемая таймером. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) конструктор

Конструктор.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, int64_t dueTime, int64_t period)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Функция, вызываемая таймером. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Аргумент функции обратного вызова. |
| dueTime | **int64_t** | [Timeout](../../timeout/) перед первым вызовом функции обратного вызова, в миллисекундах; отрицательные значения не планируют таймер после создания, поэтому его можно перенести позже. |
| period | **int64_t** | [Timeout](../../timeout/) между последовательными вызовами функции обратного вызова, в миллисекундах; неположительные значения означают, что таймер будет выполнен только один раз. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) конструктор

Конструктор.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, System::TimeSpan dueTime, System::TimeSpan period)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Функция, вызываемая таймером. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Аргумент функции обратного вызова. |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) перед первым вызовом функции обратного вызова; отрицательные значения не планируют таймер после создания, поэтому его можно перенести позже. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) между последовательными вызовами функции обратного вызова; неположительные значения означают, что таймер будет выполнен только один раз. |

## См. также

* Typedef [TimerCallback](../../timercallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Timer](../)
* Класс [Object](../../../system/object/)
* Класс [TimeSpan](../../../system/timespan/)
* Пространство имён [System::Threading](../../)
* Библиотека [Aspose.Slides](../../../)