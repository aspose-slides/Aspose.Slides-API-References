---
title: EndRead()
second_title: مرجع API Aspose.Slides برای C++
description: تا زمانی که عملیات خواندن ناهمزمان مشخص‌شده تکمیل شود، صبر می‌کند.
type: docs
weight: 261
url: /fa/system.net.sockets/networkstream/endread/
---
## NetworkStream::EndRead(System::SharedPtr\<IAsyncResult\>) متد

تا زمانی که عملیات خواندن ناهمزمان مشخص‌شده تکمیل شود، صبر می‌کند.

```cpp
int32_t System::Net::Sockets::NetworkStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | یک شیء [IAsyncResult](../../../system/iasyncresult/) که نمایانگر یک عملیات خواندن ناهمزمان است |

### مقدار بازگشت

تعداد بایت‌های خوانده‌شده در طول عملیات خواندن که توسط **asyncResult** نشان داده می‌شود

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IAsyncResult](../../../system/iasyncresult/)
* کلاس [NetworkStream](../)
* فضای‌نام [System::Net::Sockets](../../)
* کتابخانه [Aspose.Slides](../../../)