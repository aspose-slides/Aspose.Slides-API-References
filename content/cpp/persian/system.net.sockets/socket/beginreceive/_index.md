---
title: BeginReceive()
second_title: مرجع API Aspose.Slides برای C++
description: یک عملیات نوشتن ناهمزمان را آغاز می‌کند.
type: docs
weight: 521
url: /fa/system.net.sockets/socket/beginreceive/
---
## Socket::BeginReceive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) متد

یک عملیات نوشتن ناهمزمان را آغاز می‌کند.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginReceive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```


### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | یک بافر که داده‌های دریافت‌شده در آن اختصاص می‌یابد. |
| offset | **int32_t** | افست برحسب بایت در آرایهٔ مشخص شده. |
| size | **int32_t** | تعداد بایت‌ها در آرایهٔ مشخص‌شده که از پارامتر 'offset' شروع می‌شود. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار دریافت. |
| callback | [AsyncCallback](../../../system/asynccallback/) | یک کال‌بکی که هنگام تکمیل عملیات صدا زده می‌شود. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | دادهٔ ارائه‌شده توسط کاربر که برای شناسایی منحصربه‌فرد هر عملیات دریافت ناهمزمان استفاده می‌شود. |

### مقدار بازگشتی

یک شیء [IAsyncResult](../../../system/iasyncresult/) که عملیات دریافت ناهمزمان آغازشده را نشان می‌دهد.

## مراجع

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* کلاس [IAsyncResult](../../../system/iasyncresult/)
* کلاس [Object](../../../system/object/)
* کلاس [Socket](../)
* فضای‌نام [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)