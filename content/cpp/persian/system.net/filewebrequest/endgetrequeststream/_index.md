---
title: EndGetRequestStream()
second_title: مرجع API Aspose.Slides برای C++
description: تا زمانی که عملیات ناهمزمان مشخص‌شده برای دریافت یک جریان تکمیل شود، صبر می‌کند.
type: docs
weight: 157
url: /fa/system.net/filewebrequest/endgetrequeststream/
---
## FileWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) متد

تا زمانی که عملیات ناهمزمان مشخص‌شده برای دریافت یک جریان تکمیل شود، صبر می‌کند.

```cpp
System::SharedPtr<IO::Stream> System::Net::FileWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | یک شیء [IAsyncResult](../../../system/iasyncresult/) که عملیات ناهمزمان برای دریافت یک جریان را نشان می‌دهد. |

### مقدار بازگشتی

جریانی برای نوشتن داده‌ها به منبع.

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Stream](../../../system.io/stream/)
* کلاس [IAsyncResult](../../../system/iasyncresult/)
* کلاس [FileWebRequest](../)
* فضای‌نام [System::Net](../../)
* کتابخانه [Aspose.Slides](../../../)