---
title: ValueTask()
second_title: Aspose.Slides C++ API 参考
description: 构造一个空的、未初始化的 ValueTask。
type: docs
weight: 1
url: /zh/system.threading.tasks/valuetask/valuetask/
---
## ValueTask::ValueTask() 构造函数

Constructs an empty, uninitialized [ValueTask](../).

```cpp
System::Threading::Tasks::ValueTask::ValueTask()
```

## 备注

The task is not completed and contains no result. Attempting to get the result will throw an exception. 

## ValueTask::ValueTask(const TaskPtr\&) 构造函数

Constructs a [ValueTask](../) from a shared pointer to a [Task](../../task/).

```cpp
System::Threading::Tasks::ValueTask::ValueTask(const TaskPtr &task)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| task | const [TaskPtr](../../../system/taskptr/)\& | 要包装的任务。对于空任务可以为 null。 |
## 备注

该 [ValueTask](../) 将表示提供的任务的状态。 

## 参见

* Typedef [TaskPtr](../../../system/taskptr/)
* Class [ValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)