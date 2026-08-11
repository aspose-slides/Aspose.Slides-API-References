---
title: BeginWrite()
second_title: مرجع API Aspose.Slides برای C++
description: یک عملیات نوشتن ناهمزمان را آغاز می‌کند.
type: docs
weight: 443
url: /fa/system.net.security/sslstream/beginwrite/
---
## SslStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) متد

یک عملیات نوشتن ناهمزمان را آغاز می‌کند.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | آرایه بایتی که داده‌ها به آن نوشته می‌شود. |
| offset | **int32_t** | مقدار افست به بایت در آرایهٔ مشخص شده. |
| count | **int32_t** | تعداد بایت‌های قابل نوشتن. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | فراخوانی که هنگام اتمام عملیات فراخوانی می‌شود. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | داده‌های فراهم‌شده توسط کاربر که برای شناسایی منحصربه‌فرد هر عملیات نوشتن ناهمزمان استفاده می‌شود. |

### مقدار بازگشت

شیء [IAsyncResult](../../../system/iasyncresult/) که نمایانگر عملیات نوشتن ناهمزمان آغاز شده است.

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* تعریف‌نوع [AsyncCallback](../../../system/asynccallback/)
* کلاس [IAsyncResult](../../../system/iasyncresult/)
* کلاس [Object](../../../system/object/)
* کلاس [SslStream](../)
* فضای‌نام [System::Net::Security](../../)
* کتابخانه [Aspose.Slides](../../../)