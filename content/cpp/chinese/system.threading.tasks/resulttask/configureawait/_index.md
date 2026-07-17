---
title: ConfigureAwait()
second_title: Aspose.Slides for C++ API 参考
description: 配置对该结果任务的 await 操作在上下文捕获方面的行为。
type: docs
weight: 27
url: /zh/system.threading.tasks/resulttask/configureawait/
---
## ResultTask::ConfigureAwait(bool) const 方法

配置对该结果任务的 await 行为，以决定上下文捕获的处理方式。

```cpp
Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> System::Threading::Tasks::ResultTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | 是否在捕获的上下文中继续执行 |

### 返回值

Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> 用于结果的已配置 awaitable

## 备注

这使得对 async/await 模式的上下文流动能够进行细粒度的控制

## 另请参见

* 类 [ConfiguredResultTaskAwaitable](../../../system.runtime.compilerservices/configuredresulttaskawaitable/)
* 类 [ResultTask](../)
* 命名空间 [System::Threading::Tasks](../../)
* 库 [Aspose.Slides](../../../)