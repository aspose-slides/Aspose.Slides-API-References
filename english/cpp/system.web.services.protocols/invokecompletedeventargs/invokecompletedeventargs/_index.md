---
title: InvokeCompletedEventArgs()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance.
type: docs
weight: 14
url: /cpp/system.web.services.protocols/invokecompletedeventargs/invokecompletedeventargs/
---
## InvokeCompletedEventArgs::InvokeCompletedEventArgs([Exception](../../../system/exception/), **bool**, [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>, [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>) constructor


Constructs a new instance.

```cpp
System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception error, bool cancelled, System::SharedPtr<Object> userState, System::ArrayPtr<System::SharedPtr<Object>> results)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| error | [Exception](../../../system/exception/) | Any error that occurred during an asynchronous operation. |
| cancelled | **bool** | A value that indicates if an asynchronous operation is canceled. |
| userState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | The optional user-supplied state object passed to the [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../../system.componentmodel/backgroundworker/runworkerasync/)([System.Object](../../../system/object/)) method. |
| results | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | A collection of asynchronous operation results. |

## See Also

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [InvokeCompletedEventArgs](../)
* Namespace [System::Web::Services::Protocols](../../)
* Library [Aspose.Slides](../../../)
