---
title: TimerQueue
second_title: Aspose.Slides for C++ API Reference
description: Queue that handles Timer objects. This is just an implementation. Timer objects register there by themselves, you don't have to do so to use them - use Timer class API instead. This is a singleton type with memory management done by access function(s). You should never create instances of it directly.
type: docs
weight: 261
url: /system.threading/timerqueue/
---
## TimerQueue class


Queue that handles [Timer](../timer/) objects. This is just an implementation. [Timer](../timer/) objects register there by themselves, you don't have to do so to use them - use [Timer](../timer/) class API instead. This is a singleton type with memory management done by access function(s). You should never create instances of it directly.

```cpp
class TimerQueue
```

## Methods

| Method | Description |
| --- | --- |
| **bool** [Add](./add/)([Timer](../timer/) *) | Registers timer in queue. |
| **bool** [Delete](./delete/)([Timer](../timer/) *) | Deletes timer from queue. |
| static [TimerQueue](./)\& [GetInstance](./getinstance/)() | Implementation singleton. |
| static void [JoinWorkerThread](./joinworkerthread/)() | Joins worker thread. Waits infinitely if required. |
| void [operator=](./operator_equal/)(const [TimerQueue](./)\&) | No copying. |
|  [TimerQueue](./timerqueue/)(const [TimerQueue](./)\&) | No copying. |
## See Also

* Namespace [System::Threading](../)
* Library [Aspose.Slides](../../)