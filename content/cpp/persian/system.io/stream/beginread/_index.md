---
title: BeginRead()
second_title: مرجع API Aspose.Slides برای C++
description: یک عملیات خواندن ناهمزمان را آغاز می‌کند.
type: docs
weight: 157
url: /fa/system.io/stream/beginread/
---
## Stream::BeginRead(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) متد

یک عملیات خواندن ناهمزمان را آغاز می‌کند.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginRead(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | یک بافر برای خواندن |
| offset | int | یک افست صفر-پایه در **buffer** که موقعیت شروع نوشتن داده‌های خوانده شده را نشان می‌دهد |
| count | int | تعداد بایت‌ها برای خواندن |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | یک کال-بک که هنگام تکمیل عملیات فراخوانی می‌شود |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | داده‌های ارائه‌شده توسط کاربر که برای شناساگری یکتا هر عملیات خواندن ناهمزمان استفاده می‌شود |

### مقدار بازگشتی

یک شیء [IAsyncResult](../../../system/iasyncresult/) که نمایانگر عملیات خواندن ناهمزمان آغاز شده است

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* تعریف‌نوع [AsyncCallback](../../../system/asynccallback/)
* کلاس [IAsyncResult](../../../system/iasyncresult/)
* کلاس [Object](../../../system/object/)
* کلاس [Stream](../)
* فضای‌نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)