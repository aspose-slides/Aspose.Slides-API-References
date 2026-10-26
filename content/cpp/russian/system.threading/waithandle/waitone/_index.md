---
title: WaitOne()
second_title: Aspose.Slides для C++ справочник API
description: Ожидает, пока дескриптор не сработает, без ограничения времени.
type: docs
weight: 27
url: /ru/system.threading/waithandle/waitone/
---
## WaitHandle::WaitOne() метод

Ожидает, пока дескриптор не сработает, без ограничения времени.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne()
```

### Возвращаемое значение

Всегда возвращает true, так как тайм-аут не происходит.

## WaitHandle::WaitOne(int) метод

Ожидает, пока дескриптор не сработает.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) для ожидания, в миллисекундах; -1 означает бесконечное ожидание, 0 — проверка и возврат, положительные значения — тайм-ауты. |

### Возвращаемое значение

True, если дескриптор сработал, false, если тайм-аут превышен.

## WaitHandle::WaitOne(TimeSpan) метод

Ожидает, пока дескриптор не сработает.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(TimeSpan timeout)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/), представляющий количество миллисекунд для ожидания, или [System::TimeSpan](../../../system/timespan/), представляющий -1 миллисекунд для бесконечного ожидания. |

### Возвращаемое значение

True, если дескриптор сработал, false, если тайм-аут превышен.

## WaitHandle::WaitOne(int, bool) метод

Ожидает, пока дескриптор не сработает.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout, bool exitContext)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) для ожидания, в миллисекундах; -1 означает бесконечное ожидание, 0 — проверка и возврат, положительные значения — тайм-ауты. |
| exitContext | **bool** | Если true, ожидание должно снять блокировку с дескриптора перед ожиданием. |

### Возвращаемое значение

True, если дескриптор сработал, false, если тайм-аут превышен.

## См. также

* Класс [WaitHandle](../)
* Класс [TimeSpan](../../../system/timespan/)
* Пространство имён [System::Threading](../../)
* Библиотека [Aspose.Slides](../../../)