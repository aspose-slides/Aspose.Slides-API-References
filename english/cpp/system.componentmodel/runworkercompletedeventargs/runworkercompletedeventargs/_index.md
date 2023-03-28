---
title: RunWorkerCompletedEventArgs()
second_title: Aspose.Slides for C++ API Reference
description: Constructor.
type: docs
weight: 1
url: /cpp/system.componentmodel/runworkercompletedeventargs/runworkercompletedeventargs/
---
## RunWorkerCompletedEventArgs::RunWorkerCompletedEventArgs(const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\&, const [System::Exception](../../../system/exception/)\&, **bool**) constructor


Constructor.

```cpp
System::ComponentModel::RunWorkerCompletedEventArgs::RunWorkerCompletedEventArgs(const System::SharedPtr<System::Object> &result, const System::Exception &error, bool canceled)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| result | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | The result of an asynchronous operation. |
| error | const [System::Exception](../../../system/exception/)\& | Any error that occurred during the asynchronous operation. |
| canceled | **bool** | A value indicating whether the asynchronous operation was canceled. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Typedef [Exception](../../../system/exception/)
* Class [RunWorkerCompletedEventArgs](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)
