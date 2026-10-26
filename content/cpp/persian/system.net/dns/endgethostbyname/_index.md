---
title: EndGetHostByName()
second_title: Aspose.Slides برای C++ مرجع API
description: تا زمانی که عملیات ناهمزمان مشخص‌شده برای ایجاد یک نمونه جدید IPHostEntry-class تکمیل شود، صبر می‌کند.
type: docs
weight: 66
url: /fa/system.net/dns/endgethostbyname/
---
## Dns::EndGetHostByName(System::SharedPtr\<IAsyncResult\>) متد

تا زمانی که عملیات ناهمزمان مشخص‌شده برای ایجاد یک نمونه جدید IPHostEntry-class کامل شود، صبر می‌کند.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndGetHostByName(System::SharedPtr<IAsyncResult> asyncResult)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | یک شیء [IAsyncResult](../../../system/iasyncresult/) که نمایانگر یک عملیات ناهمزمان است. |

### مقدار بازگشت

یک نمونه جدید IPHostEntry-class ایجاد شده.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPHostEntry](../../iphostentry/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)