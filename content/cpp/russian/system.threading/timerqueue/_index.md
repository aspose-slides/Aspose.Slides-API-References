---
title: TimerQueue
second_title: Справочник API Aspose.Slides для C++
description: Очередь, обрабатывающая объекты Timer. Это просто реализация. Объекты Timer регистрируются там самостоятельно, вам не нужно делать это для их использования — используйте API класса Timer вместо этого. Это тип singleton с управлением памятью через функции доступа. Вам никогда не следует создавать его экземпляры напрямую.
type: docs
weight: 261
url: /ru/system.threading/timerqueue/
---
## TimerQueue класс

Queue that handles [Timer](../timer/) objects. This is just an implementation. [Timer](../timer/) objects register there by themselves, you don't have to do so to use them - use [Timer](../timer/) class API instead. This is a singleton type with memory management done by access function(s). You should never create instances of it directly.

```cpp
class TimerQueue
```

## Методы

| Метод | Описание |
| --- | --- |
| **bool** [Add](./add/)([Timer](../timer/) *) | Регистрирует таймер в очереди. |
| **bool** [Delete](./delete/)([Timer](../timer/) *) | Удаляет таймер из очереди. |
| static [TimerQueue](./)\& [GetInstance](./getinstance/)() | Синглтон реализации. |
| static void [JoinWorkerThread](./joinworkerthread/)() | Присоединяет рабочий поток. Ожидает бесконечно, если требуется. |
| void [operator=](./operator_equal/)(const [TimerQueue](./)\&) | Без копирования. |
|  [TimerQueue](./timerqueue/)(const [TimerQueue](./)\&) | Без копирования. |

## См. также

* Пространство имён [System::Threading](../)
* Библиотека [Aspose.Slides](../../)