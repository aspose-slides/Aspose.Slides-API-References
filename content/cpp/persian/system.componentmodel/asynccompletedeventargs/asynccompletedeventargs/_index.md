---
title: AsyncCompletedEventArgs()
second_title: مرجع API Aspose.Slides برای C++
description: سازنده.
type: docs
weight: 1
url: /fa/system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/
---
## AsyncCompletedEventArgs::AsyncCompletedEventArgs() سازنده

سازنده.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs()
```

## AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) سازنده

یک نمونه جدید از کلاس [System.ComponentModel.AsyncCompletedEventArgs](../) را مقداردهی اولیه می‌کند.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception &error, bool canceled, const System::SharedPtr<System::Object> &userState)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| error | const [System::Exception](../../../system/exception/)\& | هر خطایی که در طول عملیات ناهمزمان رخ داده است. |
| canceled | **bool** | یک مقدار که نشان می‌دهد آیا عملیات ناهمزمان لغو شده است یا خیر. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | شیء وضعیت اختیاری فراهم شده توسط کاربر که به متد [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../backgroundworker/runworkerasync/)([System.Object](../../../system/object/)) پاس داده می‌شود. |

## مراجعه

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [AsyncCompletedEventArgs](../)
* کلاس [Object](../../../system/object/)
* فضای نام [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)