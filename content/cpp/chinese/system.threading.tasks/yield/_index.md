---
title: Yield()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个可等待的任务，在等待时异步返回到当前上下文。
type: docs
weight: 222
url: /zh/system.threading.tasks/yield/
---
## System::Threading::Tasks::Yield() 函数

创建一个可等待的任务，在等待时异步返回到当前上下文。

```cpp
Runtime::CompilerServices::YieldAwaitable System::Threading::Tasks::Yield()
```

### 返回值

一个 YieldAwaitable，可被等待以让出控制权。

## 备注

此方法用于强制异步方法让出控制权，以便在继续之前处理其他挂起的工作。

## 参见

* 类 [YieldAwaitable](../../system.runtime.compilerservices/yieldawaitable/)
* 命名空间 [System::Threading::Tasks](../)
* 库 [Aspose.Slides](../../)