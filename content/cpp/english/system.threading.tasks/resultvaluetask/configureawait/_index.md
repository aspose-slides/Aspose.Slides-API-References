---
title: ConfigureAwait()
second_title: Aspose.Slides for C++ API Reference
description: Configures an awaiter for this task.
type: docs
weight: 92
url: /system.threading.tasks/resultvaluetask/configureawait/
---
## ResultValueTask::ConfigureAwait(bool) const method


Configures an awaiter for this task.

```cpp
Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable<T> System::Threading::Tasks::ResultValueTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true to attempt to marshal the continuation back to the original context captured; otherwise, false. |

### Return Value

ConfiguredResultValueTaskAwaitable<T> An object that configures how awaiters behave for this task.

## See Also

* Class [ConfiguredResultValueTaskAwaitable](../../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)
* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)