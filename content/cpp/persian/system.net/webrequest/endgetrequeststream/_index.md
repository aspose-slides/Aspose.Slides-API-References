---
title: EndGetRequestStream()
second_title: Aspose.Slides برای مرجع API C++
description: تا زمانی که عملیات ناهمزمان مشخص‌شده برای دریافت یک جریان کامل شود، منتظر می‌ماند.
type: docs
weight: 313
url: /fa/system.net/webrequest/endgetrequeststream/
---
## WebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) متد

تا زمانی که عملیات ناهمزمان مشخص‌شده برای دریافت یک جریان کامل شود، منتظر می‌ماند.

```cpp
virtual System::SharedPtr<IO::Stream> System::Net::WebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | یک شیء [IAsyncResult](../../../system/iasyncresult/) که نمایانگر یک عملیات ناهمزمان برای دریافت یک جریان است. |

### مقدار بازگشتی

جریان برای نوشتن داده‌ها به منبع.

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Stream](../../../system.io/stream/)
* کلاس [IAsyncResult](../../../system/iasyncresult/)
* کلاس [WebRequest](../)
* فضای‌نام [System::Net](../../)
* کتابخانه [Aspose.Slides](../../../)