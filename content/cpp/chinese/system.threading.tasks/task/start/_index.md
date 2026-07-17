---
title: Start()
second_title: Aspose.Slides for C++ API 参考
description: 使用默认调度器启动任务执行。
type: docs
weight: 170
url: /zh/system.threading.tasks/task/start/
---
## Task::Start() 方法

使用默认调度器启动任务执行。

```cpp
void System::Threading::Tasks::Task::Start()
```

## Task::Start(const SharedPtr\<TaskScheduler\>\&) 方法

使用指定的调度器启动任务执行。

```cpp
void System::Threading::Tasks::Task::Start(const SharedPtr<TaskScheduler> &scheduler)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scheduler | const [SharedPtr](../../../system/sharedptr/)\<[TaskScheduler](../../taskscheduler/)\>\& | 用于执行的调度器 |

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Task](../)
* Class [TaskScheduler](../../taskscheduler/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)