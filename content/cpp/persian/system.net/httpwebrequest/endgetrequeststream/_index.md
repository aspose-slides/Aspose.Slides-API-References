---
title: EndGetRequestStream()
second_title: Aspose.Slides برای C++ مرجع API
description: تا زمانی که عملیات ناهمزمان مشخص‌شده برای دریافت یک جریان تکمیل شود، صبر می‌کند.
type: docs
weight: 482
url: /fa/system.net/httpwebrequest/endgetrequeststream/
---
## HttpWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) متد

تا زمانی که عملیات ناهمزمان مشخص‌شده برای دریافت یک جریان تکمیل شود، صبر می‌کند.

```cpp
System::SharedPtr<IO::Stream> System::Net::HttpWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | یک شیء [IAsyncResult](../../../system/iasyncresult/) که نمایانگر یک عملیات ناهمزمان برای دریافت یک جریان است. |

### مقدار بازگشتی

جریان برای نوشتن داده‌ها به منبع.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Stream](../../../system.io/stream/)
* کلاس [IAsyncResult](../../../system/iasyncresult/)
* کلاس [HttpWebRequest](../)
* فضای‌نام [System::Net](../../)
* کتابخانه [Aspose.Slides](../../../)