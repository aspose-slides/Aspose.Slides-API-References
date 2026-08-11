---
title: BeginRead()
second_title: Aspose.Slides برای C++ مرجع API
description: یک عملیات خواندن غیرهمزمان را آغاز می‌کند.
type: docs
weight: 248
url: /fa/system.net.sockets/networkstream/beginread/
---
## NetworkStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) متد

یک عملیات خواندن غیرهمزمان را آغاز می‌کند.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | آرایه بایتی که بایت‌های خوانده‌شده در آن نوشته می‌شوند. |
| offset | **int32_t** | افست به بایت در آرایهٔ مشخص شده. |
| size | **int32_t** | تعداد بایت‌های قابل خواندن. |
| callback | [AsyncCallback](../../../system/asynccallback/) | یک callback که وقتی عملیات تمام شد فراخوانی می‌شود. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | داده‌های ارائه‌شده توسط کاربر که برای شناسایی یکتای هر عملیات خواندن غیرهمزمان استفاده می‌شود. |

### مقدار بازگشتی

یک شیء [IAsyncResult](../../../system/iasyncresult/) که نمایانگر عملیات خواندن غیرهمزمان آغاز شده است.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)