---
title: GetAwaiter()
second_title: Aspose.Slides for C++ API 参考
description: 获取此结果任务的 awaiter，以便与 Await 一起使用。
type: docs
weight: 53
url: /zh/system.threading.tasks/resulttask/getawaiter/
---
## ResultTask::GetAwaiter() const 方法

获取此结果任务的 awaiter，以便与 Await 一起使用。

```cpp
Runtime::CompilerServices::ResultTaskAwaiter<T> System::Threading::Tasks::ResultTask<T>::GetAwaiter() const
```

### 返回值

Runtime::CompilerServices::ResultTaskAwaiter<T> 返回结果的 awaiter 实例

## 备注

当被 await 时，协程将在结果值可用时恢复

## 另见

* 类 [ResultTaskAwaiter](../../../system.runtime.compilerservices/resulttaskawaiter/)
* 类 [ResultTask](../)
* 命名空间 [System::Threading::Tasks](../../)
* 库 [Aspose.Slides](../../../)