---
title: GetAwaiter()
second_title: Aspose.Slides for C++ API 参考
description: 获取此任务的 awaiter，以支持 await 表达式。
type: docs
weight: 118
url: /zh/system.threading.tasks/resultvaluetask/getawaiter/
---
## ResultValueTask::GetAwaiter() const 方法


获取此任务的 awaiter，以支持 await 表达式。

```cpp
Runtime::CompilerServices::ResultValueTaskAwaiter<T> System::Threading::Tasks::ResultValueTask<T>::GetAwaiter() const
```


### 返回值

ResultValueTaskAwaiter<T> 此任务的 awaiter 实例。
## 备注


此方法使得能够在 [ResultValueTask](../) 中使用 Await 方法。 

## 另见

* 类 [ResultValueTaskAwaiter](../../../system.runtime.compilerservices/resultvaluetaskawaiter/)
* 类 [ResultValueTask](../)
* 命名空间 [System::Threading::Tasks](../../)
* 库 [Aspose.Slides](../../../)