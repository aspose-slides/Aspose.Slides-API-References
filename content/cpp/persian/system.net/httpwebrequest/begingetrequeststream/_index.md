---
title: BeginGetRequestStream()
second_title: مرجع API Aspose.Slides برای C++
description: عملیات ناهمزمانی را برای دریافت یک جریان جهت نوشتن داده‌ها به منبع آغاز می‌کند.
type: docs
weight: 469
url: /fa/system.net/httpwebrequest/begingetrequeststream/
---
## HttpWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) متد

یک عملیات ناهمزمان را برای دریافت یک جریان به منظور نوشتن داده‌ها به منبع آغاز می‌کند.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### پارامترها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | یک تابع بازخوانی که وقتی عملیات تکمیل شد فراخوانی می‌شود. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | داده‌های ارائه‌شده توسط کاربر که برای شناسایی یکتای هر عملیات ناهمزمان استفاده می‌شوند. |

### مقدار بازگشت

یک [IAsyncResult](../../../system/iasyncresult/) شیء که نمایانگر عملیات ناهمزمان آغاز شده است.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* کلاس [IAsyncResult](../../../system/iasyncresult/)
* کلاس [Object](../../../system/object/)
* کلاس [HttpWebRequest](../)
* فضای نام [System::Net](../../)
* Library [Aspose.Slides](../../../)