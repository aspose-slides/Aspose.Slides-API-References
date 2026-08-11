---
title: BeginGetHostByName()
second_title: مرجع API Aspose.Slides برای C++
description: یک عملیات ناهمزمان را برای ایجاد یک نمونه جدید از کلاس IPHostEntry با استفاده از نام میزبان مشخص‌شده آغاز می‌کند.
type: docs
weight: 53
url: /fa/system.net/dns/begingethostbyname/
---
## Dns::BeginGetHostByName(String, AsyncCallback, System::SharedPtr\<Object\>) متد

یک عملیات ناهمزمان را برای ایجاد یک نمونه جدید IPHostEntry-کلاس با استفاده از نام میزبان مشخص شده آغاز می‌کند.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostByName(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | یک نام میزبان. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | یک کال‌بک که هنگام اتمام عملیات فراخوانی می‌شود. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | داده‌های ارائه‌شده توسط کاربر که برای تشخیص یکتای هر عملیات ناهمزمان استفاده می‌شوند. |

### Return Value

یک شیء [IAsyncResult](../../../system/iasyncresult/) که نمایانگر عملیات ناهمزمان آغاز شده است.

## See Also

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* تعریف‌نوع [AsyncCallback](../../../system/asynccallback/)
* کلاس [IAsyncResult](../../../system/iasyncresult/)
* کلاس [String](../../../system/string/)
* کلاس [Object](../../../system/object/)
* کلاس [Dns](../)
* فضای‌نام [System::Net](../../)
* کتابخانه [Aspose.Slides](../../../)