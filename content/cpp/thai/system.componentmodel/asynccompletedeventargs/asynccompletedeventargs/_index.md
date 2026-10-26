---
title: AsyncCompletedEventArgs()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: คอนสตรัคเตอร์.
type: docs
weight: 1
url: /th/system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/
---
## AsyncCompletedEventArgs::AsyncCompletedEventArgs() คอนสตรัคเตอร์


Constructor.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs()
```

## AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) คอนสตรัคเตอร์


Initializes a new instance of the [System.ComponentModel.AsyncCompletedEventArgs](../) class.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception &error, bool canceled, const System::SharedPtr<System::Object> &userState)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| error | const [System::Exception](../../../system/exception/)\& | Any error that occurred during the asynchronous operation. |
| canceled | **bool** | A value indicating whether the asynchronous operation was canceled. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | The optional user-supplied state object passed to the [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../backgroundworker/runworkerasync/)([System.Object](../../../system/object/)) method. |

## ดูเพิ่มเติม

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [AsyncCompletedEventArgs](../)
* Class [Object](../../../system/object/)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)