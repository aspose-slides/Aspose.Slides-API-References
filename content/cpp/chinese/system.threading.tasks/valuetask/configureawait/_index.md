---
title: ConfigureAwait()
second_title: Aspose.Slides for C++ API 参考
description: 为此任务配置 awaiter。
type: docs
weight: 79
url: /zh/system.threading.tasks/valuetask/configureawait/
---
## ValueTask::ConfigureAwait(bool) const 方法

配置此任务的 awaiter。

```cpp
Runtime::CompilerServices::ConfiguredValueTaskAwaitable System::Threading::Tasks::ValueTask::ConfigureAwait(bool continueOnCapturedContext) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true 表示尝试将后续操作重新调度回原始捕获的上下文；否则为 false。 |

### 返回值

ConfiguredValueTaskAwaitable 一个配置 awaiter 行为的对象，用于此任务。

## 另请参见

* 类 [ConfiguredValueTaskAwaitable](../../../system.runtime.compilerservices/configuredvaluetaskawaitable/)
* 类 [ValueTask](../)
* 命名空间 [System::Threading::Tasks](../../)
* 库 [Aspose.Slides](../../../)