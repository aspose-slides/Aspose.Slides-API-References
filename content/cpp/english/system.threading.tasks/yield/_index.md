---
title: Yield()
second_title: Aspose.Slides for C++ API Reference
description: Creates an awaitable task that asynchronously yields back to the current context when awaited.
type: docs
weight: 222
url: /system.threading.tasks/yield/
---
## System::Threading::Tasks::Yield() function


Creates an awaitable task that asynchronously yields back to the current context when awaited.

```cpp
Runtime::CompilerServices::YieldAwaitable System::Threading::Tasks::Yield()
```


### Return Value

A YieldAwaitable that can be awaited to yield control.
## Remarks



This method is useful for forcing an asynchronous method to yield control, allowing other pending work to be processed before continuing. 
## See Also

* Class [YieldAwaitable](../../system.runtime.compilerservices/yieldawaitable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)