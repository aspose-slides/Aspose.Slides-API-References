---
title: QueueUserWorkItem()
second_title: Aspose.Slides for C++ API Reference
description: Puts work item into queue which is present with callback with no parameter.
type: docs
weight: 14
url: /system.threading/threadpool/queueuserworkitem/
---
## ThreadPool::QueueUserWorkItem(WaitCallback) method


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

## ThreadPool::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) method


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
* Class [ThreadPool](../)
* Class [Object](../../../system/object/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)