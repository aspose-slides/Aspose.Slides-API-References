---
title: BeginWrite()
second_title: مرجع API Aspose.Slides برای C++
description: یک عملیات نوشتن ناهمگام را آغاز می‌کند.
type: docs
weight: 274
url: /fa/system.net.sockets/networkstream/beginwrite/
---
## NetworkStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) متد

یک عملیات نوشتن ناهمگام را آغاز می‌کند.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بوفری شامل داده‌های قابل نوشتن. |
| offset | **int32_t** | مقدار offset به بایت در آرایهٔ مشخص‌شده. |
| size | **int32_t** | تعداد بایت‌ها برای نوشتن. |
| callback | [AsyncCallback](../../../system/asynccallback/) | یک callback که هنگام کامل شدن عملیات فراخوانی می‌شود. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | داده‌ای که توسط کاربر فراهم شده و برای شناسایی یکتا هر عملیات نوشتن ناهمگام استفاده می‌شود. |

### مقدار بازگشت

شیء [IAsyncResult](../../../system/iasyncresult/) که نمایانگر عملیات نوشتن ناهمگام آغاز شده است.

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)