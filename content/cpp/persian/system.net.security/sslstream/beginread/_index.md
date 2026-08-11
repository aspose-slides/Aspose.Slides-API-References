---
title: BeginRead()
second_title: مرجع API Aspose.Slides برای C++
description: یک عملیات خواندن ناهمگام را آغاز می‌کند.
type: docs
weight: 417
url: /fa/system.net.security/sslstream/beginread/
---
## SslStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) متد

یک عملیات خواندن ناهمگام را آغاز می‌کند.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | آرایه بایتی که داده‌ها از آن خوانده می‌شود. |
| offset | **int32_t** | افست به بایت در آرایهٔ مشخص شده. |
| count | **int32_t** | تعداد بایت‌هایی که باید خوانده شوند. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | یک کال‌بک که پس از تکمیل عملیات فراخوانی می‌شود. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | داده‌های فراهم‌شده توسط کاربر که برای شناسایی یکتا هر عملیات خواندن ناهمگام استفاده می‌شود. |

### مقدار بازگشتی

یک شیء [IAsyncResult](../../../system/iasyncresult/) که عملیات خواندن ناهمگام آغاز شده را نشان می‌دهد.

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)