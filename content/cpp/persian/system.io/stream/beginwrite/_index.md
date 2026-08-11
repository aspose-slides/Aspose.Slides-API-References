---
title: BeginWrite()
second_title: Aspose.Slides برای مرجع API C++
description: یک عملیات نوشتن ناهمزمان را آغاز می‌کند.
type: docs
weight: 170
url: /fa/system.io/stream/beginwrite/
---
## Stream::BeginWrite(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) متد

یک عملیات نوشتن ناهمزمان را آغاز می‌کند.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | یک بافر حاوی داده‌هایی که باید نوشته شوند |
| offset | int | افست مبتنی بر ۰ در **buffer** که موقعیتی را که داده‌ها از آنجا نوشته می‌شوند نشان می‌دهد |
| count | int | تعداد بایت‌هایی که باید نوشته شوند |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | یک بازخوانی که هنگام تکمیل عملیات فراخوانی می‌شود |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | داده‌های ارائه‌شده توسط کاربر برای شناسایی یکتا هر عملیات نوشتن ناهمزمان |

### مقدار بازگشتی

یک شیء [IAsyncResult](../../../system/iasyncresult/) که نمایانگر عملیات نوشتن ناهمزمان آغاز شده است

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* کلاس [IAsyncResult](../../../system/iasyncresult/)
* کلاس [Object](../../../system/object/)
* کلاس [Stream](../)
* فضای نام [System::IO](../../)
* Library [Aspose.Slides](../../../)