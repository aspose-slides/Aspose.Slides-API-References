---
title: EndGetHostAddresses()
second_title: مرجع API Aspose.Slides برای C++
description: صبر می‌کند تا عملیات ناهمزمان تعیین‌شده برای ایجاد یک نمونه جدید IPHostEntry-class تکمیل شود.
type: docs
weight: 144
url: /fa/system.net/dns/endgethostaddresses/
---
## Dns::EndGetHostAddresses(System::SharedPtr\<IAsyncResult\>) متد

صبر می‌کند تا عملیات ناهمزمان مشخص شده برای ایجاد یک نمونه جدید IPHostEntry-class تکمیل شود.

```cpp
static System::ArrayPtr<System::SharedPtr<IPAddress>> System::Net::Dns::EndGetHostAddresses(System::SharedPtr<IAsyncResult> asyncResult)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | یک شیء [IAsyncResult](../../../system/iasyncresult/) که یک عملیات ناهمزمان را نشان می‌دهد. |

### مقدار بازگشتی

یک نمونه جدید IPHostEntry-class ایجاد شده.

## موارد مرتبط

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IPAddress](../../ipaddress/)
* کلاس [IAsyncResult](../../../system/iasyncresult/)
* کلاس [Dns](../)
* فضای‌نام [System::Net](../../)
* کتابخانه [Aspose.Slides](../../../)