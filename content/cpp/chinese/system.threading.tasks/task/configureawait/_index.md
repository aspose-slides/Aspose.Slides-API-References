---
title: ConfigureAwait()
second_title: Aspose.Slides for C++ API 参考
description: 配置此任务上的 await 在上下文捕获方面的行为方式。
type: docs
weight: 144
url: /zh/system.threading.tasks/task/configureawait/
---
## Task::ConfigureAwait(bool) const 方法


配置此任务上的 await 在上下文捕获方面的行为方式。

```cpp
Runtime::CompilerServices::ConfiguredTaskAwaitable System::Threading::Tasks::Task::ConfigureAwait(bool continueOnCapturedContext) const
```


### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | 是否在捕获的上下文中继续执行 |

### 返回值

[Runtime::CompilerServices::ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/) 一个已配置的可等待对象

## 另请参见

* 类 [ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/)
* 类 [Task](../)
* 命名空间 [System::Threading::Tasks](../../)
* 库 [Aspose.Slides](../../../)