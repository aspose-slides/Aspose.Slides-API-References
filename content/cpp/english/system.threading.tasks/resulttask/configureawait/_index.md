---
title: ConfigureAwait()
second_title: Aspose.Slides for C++ API Reference
description: Configures how awaits on this result task should behave regarding context capture.
type: docs
weight: 27
url: /system.threading.tasks/resulttask/configureawait/
---
## ResultTask::ConfigureAwait(bool) const method


Configures how awaits on this result task should behave regarding context capture.

```cpp
Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> System::Threading::Tasks::ResultTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | Whether to continue on the captured context |

### Return Value

Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> A configured awaitable for the result
## Remarks



This enables fine-grained control over context flow for async/await patterns 

## See Also

* Class [ConfiguredResultTaskAwaitable](../../../system.runtime.compilerservices/configuredresulttaskawaitable/)
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)