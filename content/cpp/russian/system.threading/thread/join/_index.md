---
title: Join()
second_title: Справочник API Aspose.Slides для C++
description: Присоединяет управляемый поток. Выполняет неограниченное ожидание, если требуется.
type: docs
weight: 196
url: /ru/system.threading/thread/join/
---
## Thread::Join() метод

Присоединяет управляемый поток. Выполняет неограниченное ожидание, если требуется.

```cpp
void System::Threading::Thread::Join()
```

## Thread::Join(int) метод

Присоединяет управляемый поток. Выполняет ограниченное ожидание.

```cpp
bool System::Threading::Thread::Join(int millisecondsTimeout)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| millisecondsTimeout | int | Тайм-аут ожидания в миллисекундах. |

### Возвращаемое значение

True, если поток был успешно присоединён, false, если время ожидания истекло.

## Thread::Join(TimeSpan) метод

Присоединяет управляемый поток. Выполняет ограниченное ожидание.

```cpp
bool System::Threading::Thread::Join(TimeSpan timeout)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | Объект [TimeSpan](../../../system/timespan/), задающий время ожидания завершения потока. |

### Возвращаемое значение

True, если поток был успешно присоединён, false, если время ожидания истекло.

## Смотрите также

* Класс [Thread](../)
* Класс [TimeSpan](../../../system/timespan/)
* Пространство имён [System::Threading](../../)
* Библиотека [Aspose.Slides](../../../)