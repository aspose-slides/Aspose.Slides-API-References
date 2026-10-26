---
title: ConfigureAwait()
second_title: Aspose.Slides for C++ API 参考
description: 为此任务配置等待器。
type: docs
weight: 92
url: /zh/system.threading.tasks/resultvaluetask/configureawait/
---
## ResultValueTask::ConfigureAwait(bool) const 方法

为此任务配置等待器。

```cpp
Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable<T> System::Threading::Tasks::ResultValueTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true 表示尝试将后续操作重新调度回捕获的原始上下文；false 表示不这样做。 |

### 返回值

ConfiguredResultValueTaskAwaitable<T> 配置等待器在此任务中行为的对象。

## 另请参见

* 类 [ConfiguredResultValueTaskAwaitable](../../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)
* 类 [ResultValueTask](../)
* 命名空间 [System::Threading::Tasks](../../)
* 库 [Aspose.Slides](../../../)