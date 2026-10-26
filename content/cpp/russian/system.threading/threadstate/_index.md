---
title: ThreadState
second_title: Справочник API Aspose.Slides для C++
description: Состояние потока.
type: docs
weight: 326
url: /ru/system.threading/threadstate/
---
## Перечисление ThreadState

Состояние потока.

```cpp
enum ThreadState
```

### Значения

| Name | Value | Description |
| --- | --- | --- |
| Running | 0 | [Thread](../thread/) работает. |
| StopRequested | 1 | [Thread](../thread/) остановка запрошена. |
| SuspendRequested | 2 | [Thread](../thread/) приостановка запрошена. |
| Background | 4 | Поток выполняется в фоновом режиме. |
| Unstarted | 8 | [Thread](../thread/) не запущен. |
| Stopped | 16 | [Thread](../thread/) остановлен. |
| WaitSleepJoin | 32 | [Thread](../thread/) ожидает присоединения. |
| Suspended | 64 | [Thread](../thread/) приостановлен. |
| AbortRequested | 128 | [Thread](../thread/) прерывание запрошено. |
| Aborted | 256 | [Thread](../thread/) прерван. |

## См. также

* Пространство имён [System::Threading](../)
* Библиотека [Aspose.Slides](../../)