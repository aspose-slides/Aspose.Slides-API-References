---
title: BeginGetResponse()
second_title: Aspose.Slides برای C++ مرجع API
description: یک درخواست غیرهمزمان برای منبع آغاز می‌کند.
type: docs
weight: 495
url: /fa/system.net/httpwebrequest/begingetresponse/
---
## HttpWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) متد

یک درخواست غیرهمزمان برای منبع آغاز می‌کند.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | یک callback که هنگام تکمیل عملیات فراخوانی می‌شود. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | داده‌ای که توسط کاربر فراهم می‌شود و برای شناسایی یکتا هر عملیات غیرهمزمان استفاده می‌شود. |

### مقدار بازگشتی

یک شیء [IAsyncResult](../../../system/iasyncresult/) که عملیات غیرهمزمان آغاز شده را نمایندگی می‌کند.

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* تعریف‌نوع [AsyncCallback](../../../system/asynccallback/)
* کلاس [IAsyncResult](../../../system/iasyncresult/)
* کلاس [Object](../../../system/object/)
* کلاس [HttpWebRequest](../)
* فضای‌نام [System::Net](../../)
* کتابخانه [Aspose.Slides](../../../)