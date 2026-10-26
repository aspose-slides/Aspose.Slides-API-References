---
title: AsTask()
second_title: Aspose.Slides for C++ API 参考
description: 将此 ResultValueTask 转换为指向 ResultTask<T> 的共享指针。
type: docs
weight: 79
url: /zh/system.threading.tasks/resultvaluetask/astask/
---
## ResultValueTask::AsTask() const 方法

将此 [ResultValueTask](../) 转换为指向 ResultTask<T> 的共享指针。

```cpp
RTaskPtr<T> System::Threading::Tasks::ResultValueTask<T>::AsTask() const
```

### 返回值

RTaskPtr<T> 表示此操作的指向 ResultTask<T> 的共享指针。

## 备注

如果 [ResultValueTask](../) 包含直接结果，则创建一个带有该结果的已完成任务。如果它包含任务，则返回指向该任务的共享指针。

## 另请参见

* 类型定义 [RTaskPtr](../../../system/rtaskptr/)
* 类 [ResultValueTask](../)
* 命名空间 [System::Threading::Tasks](../../)
* 库 [Aspose.Slides](../../../)