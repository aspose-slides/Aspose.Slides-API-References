---
title: AsyncCompletedEventArgs()
second_title: Aspose.Slides for C++ API Reference
description: Constructor.
type: docs
weight: 1
url: /system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/
---
## AsyncCompletedEventArgs::AsyncCompletedEventArgs() constructor


Constructor.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs()
```

## AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) constructor


Initializes a new instance of the [System.ComponentModel.AsyncCompletedEventArgs](../) class.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception &error, bool canceled, const System::SharedPtr<System::Object> &userState)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| error | const [System::Exception](../../../system/exception/)\& | Any error that occurred during the asynchronous operation. |
| canceled | **bool** | A value indicating whether the asynchronous operation was canceled. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | The optional user-supplied state object passed to the [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../backgroundworker/runworkerasync/)([System.Object](../../../system/object/)) method. |

## See Also

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [AsyncCompletedEventArgs](../)
* Class [Object](../../../system/object/)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)