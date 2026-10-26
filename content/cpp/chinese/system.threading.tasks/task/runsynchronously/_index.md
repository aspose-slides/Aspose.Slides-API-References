---
title: RunSynchronously()
second_title: Aspose.Slides for C++ API 参考
description: 在当前线程上同步运行任务。
type: docs
weight: 157
url: /zh/system.threading.tasks/task/runsynchronously/
---
## Task::RunSynchronously() 方法

在当前线程上同步运行任务。

```cpp
void System::Threading::Tasks::Task::RunSynchronously()
```

## Task::RunSynchronously(const SharedPtr\<TaskScheduler\>\&) 方法

使用指定的调度程序同步运行任务。

```cpp
void System::Threading::Tasks::Task::RunSynchronously(const SharedPtr<TaskScheduler> &scheduler)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scheduler | const [SharedPtr](../../../system/sharedptr/)\<[TaskScheduler](../../taskscheduler/)\>\& | 用于执行的调度程序 |

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Task](../)
* 类 [TaskScheduler](../../taskscheduler/)
* 命名空间 [System::Threading::Tasks](../../)
* 库 [Aspose.Slides](../../../)