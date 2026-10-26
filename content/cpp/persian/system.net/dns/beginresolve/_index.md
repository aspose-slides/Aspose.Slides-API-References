---
title: BeginResolve()
second_title: مرجع API Aspose.Slides برای C++
description: یک عملیات ناهمزمان را برای ایجاد یک نمونه جدید از کلاس IPHostEntry-class با استفاده از نام میزبان مشخص‌شده آغاز می‌کند.
type: docs
weight: 157
url: /fa/system.net/dns/beginresolve/
---
## Dns::BeginResolve(String, AsyncCallback, System::SharedPtr\<Object\>) متد


یک عملیات ناهمزمان را برای ایجاد یک نمونه جدید از کلاس IPHostEntry-class با استفاده از نام میزبان مشخص شده آغاز می‌کند.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginResolve(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | یک نام میزبان که برای ایجاد یک نمونه جدید از کلاس [IPHostEntry](../../iphostentry/) استفاده می‌شود. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | یک فراخوانی که هنگام اتمام عملیات فراخوانی می‌شود. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | داده‌ای که توسط کاربر فراهم شده برای شناسایی یکتا هر عملیات ناهمزمان استفاده می‌شود. |

### مقدار بازگشت

یک شیء [IAsyncResult](../../../system/iasyncresult/) که نمایانگر عملیات ناهمزمان آغاز شده است.

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* تعریف نوع [AsyncCallback](../../../system/asynccallback/)
* کلاس [IAsyncResult](../../../system/iasyncresult/)
* کلاس [String](../../../system/string/)
* کلاس [Object](../../../system/object/)
* کلاس [Dns](../)
* فضای نام [System::Net](../../)
* کتابخانه [Aspose.Slides](../../../)