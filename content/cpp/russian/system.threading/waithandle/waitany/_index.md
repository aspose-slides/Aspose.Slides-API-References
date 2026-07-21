---
title: WaitAny()
second_title: Справочник API Aspose.Slides для C++
description: Ожидает, пока любой из дескрипторов не сработает.
type: docs
weight: 14
url: /ru/system.threading/waithandle/waitany/
---
## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) method

Ожидает, пока любой из дескрипторов не сработает.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\& | Дескрипторы, которые нужно ожидать. |
| millisecondsTimeout | int | [Timeout](../../timeout/) to wait for, in milliseconds; -1 means infinite waiting, 0 means check-and-return, positive values are timeouts. |

### Возвращаемое значение

True, если любой дескриптор сработал, false, если превышен тайм-аут.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) method

Ожидает, пока любой из дескрипторов не сработает.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\& | Дескрипторы, которые нужно ожидать. |
| timeout | [TimeSpan](../../../system/timespan/) | A [System::TimeSpan](../../../system/timespan/) that represents the number of milliseconds to wait, or a [System::TimeSpan](../../../system/timespan/) that represents -1 milliseconds to wait indefinitely. |

### Возвращаемое значение

True, если любой дескриптор сработал, false, если превышен тайм-аут.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) method

Ожидает, пока любой из дескрипторов не сработает.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\& | Дескрипторы, которые нужно ожидать. |

### Возвращаемое значение

True, когда каждый элемент в waitHandles получил сигнал; в противном случае метод никогда не возвращает управление.

## См. также

* Типовое определение [ArrayPtr](../../../system/arrayptr/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [WaitHandle](../)
* Класс [TimeSpan](../../../system/timespan/)
* Пространство имён [System::Threading](../../)
* Библиотека [Aspose.Slides](../../../)