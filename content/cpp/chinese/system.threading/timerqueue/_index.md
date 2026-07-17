---
title: TimerQueue
second_title: Aspose.Slides for C++ API 参考
description: 处理 Timer 对象的队列。这只是一个实现。Timer 对象会自行注册到此处，您无需自行注册即可使用它们——请改用 Timer 类 API。它是一种单例类型，内存管理由访问函数完成。您不应直接创建其实例。
type: docs
weight: 261
url: /zh/system.threading/timerqueue/
---
## TimerQueue 类

处理 [Timer](../timer/) 对象的队列。这只是一个实现。[Timer](../timer/) 对象会自行注册到此处，您无需自行注册即可使用它们——请改用 [Timer](../timer/) 类 API。它是一种单例类型，内存管理由访问函数完成。您不应直接创建其实例。

```cpp
class TimerQueue
```

## 方法

| 方法 | 描述 |
| --- | --- |
| **bool** [Add](./add/)([Timer](../timer/) *) | 在队列中注册计时器。 |
| **bool** [Delete](./delete/)([Timer](../timer/) *) | 从队列中删除计时器。 |
| static [TimerQueue](./)\& [GetInstance](./getinstance/)() | 实现单例。 |
| static void [JoinWorkerThread](./joinworkerthread/)() | 加入工作线程。如有需要，无限等待。 |
| void [operator=](./operator_equal/)(const [TimerQueue](./)\&) | 不进行复制。 |
|  [TimerQueue](./timerqueue/)(const [TimerQueue](./)\&) | 不进行复制。 |

## 另见

* 命名空间 [System::Threading](../)
* 库 [Aspose.Slides](../../)