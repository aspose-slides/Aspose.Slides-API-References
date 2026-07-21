---
title: ThreadPoolImpl
second_title: Aspose.Slides для C++ справка по API
description: Внутренние данные пула потоков. Это тип-синглтон с управлением памятью, осуществляемым через функции доступа. Никогда не следует создавать его экземпляры напрямую.
type: docs
weight: 235
url: /ru/system.threading/threadpoolimpl/
---
## ThreadPoolImpl класс

[Thread](../thread/) внутренние данные пула. Это тип-синглтон с управлением памятью, осуществляемым через функции доступа. Никогда не следует создавать его экземпляры напрямую.

```cpp
class ThreadPoolImpl
```

## Методы

| Метод | Описание |
| --- | --- |
| void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | Возвращает количество доступных потоков. |
| static **bool**\& [GetInitialized](./getinitialized/)() | Возвращает синглтон состояния инициализации. |
| void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | Возвращает максимальное число одновременно работающих потоков. |
| void [GetMinThreads](./getminthreads/)(int\&, int\&) | Возвращает минимальное число потоков, создаваемых пулом. |
| void [JoinAll](./joinall/)() | Ожидает завершения всех принадлежащих потоков. Ожидает бесконечно. |
| **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Добавляет элемент работы в очередь. |
| **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | Устанавливает количество потоков, принадлежащих пулу. |
| **bool** [SetMinThreads](./setminthreads/)(int, int) | Устанавливает минимальное количество потоков, принадлежащих пулу. |
|  [ThreadPoolImpl](./threadpoolimpl/)() | Конструктор. |
|  [~ThreadPoolImpl](./~threadpoolimpl/)() | Деструктор. Ожидает завершения всех потоков, если они ещё не завершены. |

## См. также

* пространство имён [System::Threading](../)
* Библиотека [Aspose.Slides](../../)