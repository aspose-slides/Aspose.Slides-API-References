---
title: BeginSend()
second_title: Aspose.Slides برای C++ مرجع API
description: یک عملیات ارسال ناهمزمان را آغاز می‌کند.
type: docs
weight: 495
url: /fa/system.net.sockets/socket/beginsend/
---
## Socket::BeginSend(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) متد

یک عملیات ارسال ناهمزمان را آغاز می‌کند.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginSend(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | یک بافر برای خواندن داده‌ها. |
| offset | **int32_t** | جای‌گیری (آفست) بر حسب بایت در آرایهٔ مشخص شده. |
| size | **int32_t** | تعداد بایت‌ها در آرایهٔ مشخص شده که از پارامتر 'offset' شروع می‌شود. |
| socketFlags | [SocketFlags](../../socketflags/) | رفتار ارسال. |
| callback | [AsyncCallback](../../../system/asynccallback/) | بازگشتی که هنگام تکمیل عملیات فراخوانی می‌شود. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | داده‌ای که توسط کاربر فراهم شده برای شناسایی یکتا هر عملیات ارسال ناهمزمان. |

### مقدار بازگشتی

یک شیء [IAsyncResult](../../../system/iasyncresult/) که عملیات ارسال ناهمسان آغاز شده را نشان می‌دهد.

## موارد مرتبط

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)