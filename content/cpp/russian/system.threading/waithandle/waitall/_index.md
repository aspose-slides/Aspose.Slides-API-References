---
title: WaitAll()
second_title: Справочник API Aspose.Slides для C++
description: Ожидает, пока все дескрипторы не сработают.
type: docs
weight: 1
url: /ru/system.threading/waithandle/waitall/
---
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) метод

Ожидает, пока все дескрипторы не сработают.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Дескрипторы для ожидания. |
| millisecondsTimeout | int | [Timeout](../../timeout/) ожидания в миллисекундах; -1 означает бесконечное ожидание, 0 — проверка и возврат, положительные значения — тайм-ауты. |

### Возвращаемое значение

True, если все дескрипторы сработали, false, если превысен тайм-аут.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) метод

Ожидает, пока все дескрипторы не сработают.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Дескрипторы для ожидания. |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/) — объект, представляющий количество миллисекунд для ожидания, либо [System::TimeSpan](../../../system/timespan/) — объект, представляющий -1 миллисекунд для бесконечного ожидания. |

### Возвращаемое значение

True, если все дескрипторы сработали, false, если превысен тайм-аут.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) метод

Ожидает, пока все дескрипторы не сработают.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Дескрипторы для ожидания. |

### Возвращаемое значение

True, когда каждый элемент в waitHandles получил сигнал; в противном случае метод никогда не возвращается.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WaitHandle](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)