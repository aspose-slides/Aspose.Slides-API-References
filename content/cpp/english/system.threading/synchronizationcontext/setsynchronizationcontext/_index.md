---
title: SetSynchronizationContext()
second_title: Aspose.Slides for C++ API Reference
description: Sets the synchronization context for the current thread.
type: docs
weight: 27
url: /system.threading/synchronizationcontext/setsynchronizationcontext/
---
## SynchronizationContext::SetSynchronizationContext(const SharedPtr\<SynchronizationContext\>\&) method


Sets the synchronization context for the current thread.

```cpp
static void System::Threading::SynchronizationContext::SetSynchronizationContext(const SharedPtr<SynchronizationContext> &syncContext)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| syncContext | const [SharedPtr](../../../system/sharedptr/)\<[SynchronizationContext](../)\>\& | The synchronization context to set for the current thread. |
## Remarks



Passing nullptr will clear the synchronization context for the current thread. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SynchronizationContext](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)