---
title: BeginGetRequestStream()
second_title: مرجع API Aspose.Slides برای C++
description: یک عملیات غیرهمزمان را برای دریافت یک جریان به منظور نوشتن داده‌ها به منبع آغاز می‌کند.
type: docs
weight: 300
url: /fa/system.net/webrequest/begingetrequeststream/
---
## WebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) متد

یک عملیات غیرهمزمان را برای دریافت یک جریان به منظور نوشتن داده‌ها به منبع آغاز می‌کند.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state)=0
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | یک callback که هنگام تکمیل عملیات فراخوانی می‌شود. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | داده‌ای که توسط کاربر فراهم شده و برای شناسایی یکتا هر عملیات غیرهمزمان استفاده می‌شود. |

### مقدار بازگشت

یک شیء [IAsyncResult](../../../system/iasyncresult/) که نمایانگر عملیات غیرهمزمان آغاز شده است.

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* تعریف نوع [AsyncCallback](../../../system/asynccallback/)
* کلاس [IAsyncResult](../../../system/iasyncresult/)
* کلاس [Object](../../../system/object/)
* کلاس [WebRequest](../)
* فضای‌نام [System::Net](../../)
* کتابخانه [Aspose.Slides](../../../)