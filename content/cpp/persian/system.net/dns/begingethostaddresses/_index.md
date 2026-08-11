---
title: BeginGetHostAddresses()
second_title: Aspose.Slides برای C++ مرجع API
description: یک عملیات ناهمزمان را برای ایجاد یک نمونه جدید از IPHostEntry-class با استفاده از رشتهٔ مشخص شده که شامل نام میزبان یا آدرس IP است، آغاز می‌کند.
type: docs
weight: 131
url: /fa/system.net/dns/begingethostaddresses/
---
## Dns::BeginGetHostAddresses(String, AsyncCallback, System::SharedPtr\<Object\>) متد

یک عملیات ناهمزمان را برای ایجاد یک نمونه جدید از IPHostEntry-class با استفاده از رشتهٔ مشخص شده که شامل نام میزبان یا آدرس IP است، آغاز می‌کند.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostAddresses(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### پارامترها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | رشته‌ای که شامل نام میزبان یا آدرس IP است. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | یک callback که هنگام تکمیل عملیات فراخوانی می‌شود. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | داده‌ای که توسط کاربر ارائه شده و برای شناسایی یکتا هر عملیات ناهمزمان استفاده می‌شود. |

### مقدار بازگشت

یک شیٔ [IAsyncResult](../../../system/iasyncresult/) که نمایانگر عملیات ناهمزمان آغاز شده است.

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* تعریف‌نوع [AsyncCallback](../../../system/asynccallback/)
* کلاس [IAsyncResult](../../../system/iasyncresult/)
* کلاس [String](../../../system/string/)
* کلاس [Object](../../../system/object/)
* کلاس [Dns](../)
* فضای‌نام [System::Net](../../)
* کتابخانه [Aspose.Slides](../../../)