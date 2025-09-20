---
title: Register()
second_title: Aspose.Slides for C++ API Reference
description: Registers a callback that will be invoked when cancellation is requested.
type: docs
weight: 40
url: /system.threading/cancellationtoken/register/
---
## CancellationToken::Register(const Action<>\&) const method


Registers a callback that will be invoked when cancellation is requested.

```cpp
CancellationTokenRegistration System::Threading::CancellationToken::Register(const Action<> &callback) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| callback | const [Action](../../../system/action/)<>\& | The Action<> to execute when cancellation is requested. |

### Return Value

A [CancellationTokenRegistration](../../cancellationtokenregistration/) object that can be used to deregister the callback.
## Remarks



If cancellation has already been requested, the callback will be invoked immediately. 

The callback should be short-lived and non-blocking as it will be executed on the thread that calls Cancel() on the [CancellationTokenSource](../../cancellationtokensource/). 

## See Also

* Typedef [Action](../../../system/action/)
* Class [CancellationTokenRegistration](../../cancellationtokenregistration/)
* Class [CancellationToken](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)