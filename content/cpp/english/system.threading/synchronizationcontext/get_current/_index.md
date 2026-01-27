---
title: get_Current()
second_title: Aspose.Slides for C++ API Reference
description: Gets the synchronization context for the current thread.
type: docs
weight: 40
url: /system.threading/synchronizationcontext/get_current/
---
## SynchronizationContext::get_Current() method


Gets the synchronization context for the current thread.

```cpp
static const SharedPtr<SynchronizationContext> & System::Threading::SynchronizationContext::get_Current()
```


### Return Value

SharedPtr<SynchronizationContext> A shared pointer to the current thread's synchronization context.
## Remarks



Returns null if no synchronization context has been set for the current thread. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SynchronizationContext](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)