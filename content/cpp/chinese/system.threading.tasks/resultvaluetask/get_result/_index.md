---
title: get_Result()
second_title: Aspose.Slides C++ API 参考
description: 获取已完成任务的结果。
type: docs
weight: 66
url: /zh/system.threading.tasks/resultvaluetask/get_result/
---
## ResultValueTask::get_Result() 方法

获取已完成任务的结果。

```cpp
T System::Threading::Tasks::ResultValueTask<T>::get_Result()
```

### 返回值

T 结果值。

## 备注

如果任务由 ResultTask<T> 支持，此方法将等待结果并将其缓存。后续调用将返回缓存的值，而无需等待。

## 另请参见

* 类 [ResultValueTask](../)
* 命名空间 [System::Threading::Tasks](../../)
* 库 [Aspose.Slides](../../../)