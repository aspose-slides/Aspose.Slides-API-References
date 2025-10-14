---
title: ConfigureAwait()
second_title: Aspose.Slides for C++ API Reference
description: Configures an awaiter for this task.
type: docs
weight: 79
url: /system.threading.tasks/valuetask/configureawait/
---
## ValueTask::ConfigureAwait(bool) const method


Configures an awaiter for this task.

```cpp
Runtime::CompilerServices::ConfiguredValueTaskAwaitable System::Threading::Tasks::ValueTask::ConfigureAwait(bool continueOnCapturedContext) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true to attempt to marshal the continuation back to the original context captured; otherwise, false. |

### Return Value

ConfiguredValueTaskAwaitable An object that configures how awaiters behave for this task.

## See Also

* Class [ConfiguredValueTaskAwaitable](../../../system.runtime.compilerservices/configuredvaluetaskawaitable/)
* Class [ValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)