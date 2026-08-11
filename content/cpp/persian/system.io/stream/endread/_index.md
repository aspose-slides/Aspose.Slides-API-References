---
title: EndRead()
second_title: مرجع API Aspose.Slides برای C++
description: تا زمانی که عملیات خواندن ناهمزمان مشخص‌شده تکمیل شود، منتظر می‌ماند.
type: docs
weight: 183
url: /fa/system.io/stream/endread/
---
## Stream::EndRead(System::SharedPtr\<System::IAsyncResult\>) متد

تا زمانی که عملیات خواندن ناهمزمان مشخص‌شده تکمیل شود، منتظر می‌ماند.

```cpp
virtual int System::IO::Stream::EndRead(System::SharedPtr<System::IAsyncResult> asyncResult)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[System::IAsyncResult](../../../system/iasyncresult/)\> | یک شیء [IAsyncResult](../../../system/iasyncresult/) که نمایانگر یک عملیات خواندن ناهمزمان است |

### مقدار بازگشت

تعداد بایت‌های خوانده‌شده در حین عملیات خواندن که توسط **asyncResult** نمایانده شده است

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IAsyncResult](../../../system/iasyncresult/)
* کلاس [Stream](../)
* فضای نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)