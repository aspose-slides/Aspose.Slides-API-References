---
title: BeginGetRequestStream()
second_title: Aspose.Slides برای C++ مرجع API
description: یک عملیات ناهمزمان را برای دریافت جریان جهت نوشتن داده‌ها به منبع آغاز می‌کند.
type: docs
weight: 144
url: /fa/system.net/filewebrequest/begingetrequeststream/
---
## FileWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) متد

یک عملیات ناهمزمان را برای دریافت جریان جهت نوشتن داده‌ها به منبع آغاز می‌کند.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | یک بازگردانی که هنگام اتمام عملیات فراخوانی می‌شود. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | داده‌های فراهم‌شده توسط کاربر که برای شناسایی یکتا هر عملیات ناهمزمان استفاده می‌شود. |

### مقدار بازگشت

یک شیء [IAsyncResult](../../../system/iasyncresult/) که عملیات ناهمزمان آغاز شده را نشان می‌دهد.

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* تعریف‌نوع [AsyncCallback](../../../system/asynccallback/)
* کلاس [IAsyncResult](../../../system/iasyncresult/)
* کلاس [Object](../../../system/object/)
* کلاس [FileWebRequest](../)
* فضای‌نام [System::Net](../../)
* کتابخانه [Aspose.Slides](../../../)