---
title: QueueUserWorkItem()
second_title: Aspose.Slides for C++ API Reference
description: Puts work item into queue which is present with callback with no parameter.
type: docs
weight: 14
url: /cpp/system.threading/threadpool/queueuserworkitem/
---
## ThreadPool::QueueUserWorkItem([WaitCallback](../../waitcallback/)) method


Puts work item into queue which is present with callback with no parameter.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Callback function to be used as a job. |

### Return Value

Always returns true.

## See Also

* Typedef [WaitCallback](../../waitcallback/)
* Class [ThreadPool](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)
## ThreadPool::QueueUserWorkItem([WaitCallback](../../waitcallback/), const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\&) method


Puts work item into queue which is present with callback with no parameter.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Callback function to be used as a job. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Job function parameter. |

### Return Value

Always returns true.

## See Also

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [ThreadPool](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)
