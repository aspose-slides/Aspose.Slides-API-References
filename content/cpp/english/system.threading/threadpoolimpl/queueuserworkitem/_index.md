---
title: QueueUserWorkItem()
second_title: Aspose.Slides for C++ API Reference
description: Adds work item to queue.
type: docs
weight: 1
url: /system.threading/threadpoolimpl/queueuserworkitem/
---
## ThreadPoolImpl::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) method


Adds work item to queue.

```cpp
bool System::Threading::ThreadPoolImpl::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Callback function to execute. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Callback function argument. |

### Return Value

Always returns true.

## See Also

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [ThreadPoolImpl](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)