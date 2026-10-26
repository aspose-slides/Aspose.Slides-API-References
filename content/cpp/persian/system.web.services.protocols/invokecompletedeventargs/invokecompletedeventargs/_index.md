---
title: InvokeCompletedEventArgs()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمونه جدید ایجاد می‌کند.
type: docs
weight: 14
url: /fa/system.web.services.protocols/invokecompletedeventargs/invokecompletedeventargs/
---
## InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception, bool, System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<Object\>\>) سازنده

Constructs a new instance.

```cpp
System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception error, bool cancelled, System::SharedPtr<Object> userState, System::ArrayPtr<System::SharedPtr<Object>> results)
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| error | [Exception](../../../system/exception/) | هر خطایی که در طول یک عملیات ناهم‌زمان رخ داده است. |
| cancelled | **bool** | مقداری که نشان می‌دهد آیا یک عملیات ناهم‌زمان لغو شده است یا خیر. |
| userState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | شیء حالت اختیاری که توسط کاربر فراهم شده و به روش [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../../system.componentmodel/backgroundworker/runworkerasync/)([System.Object](../../../system/object/)) ارسال می‌شود. |
| results | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | مجموعه‌ای از نتایج عملیات ناهم‌زمان. |

## همچنین ببینید

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [Object](../../../system/object/)
* کلاس [InvokeCompletedEventArgs](../)
* فضای‌نام [System::Web::Services::Protocols](../../)
* کتابخانه [Aspose.Slides](../../../)