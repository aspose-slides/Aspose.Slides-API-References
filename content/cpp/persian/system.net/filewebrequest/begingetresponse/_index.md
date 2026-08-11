---
title: BeginGetResponse()
second_title: مرجع API Aspose.Slides برای C++
description: یک درخواست ناهمزمان برای منبع را آغاز می‌کند.
type: docs
weight: 170
url: /fa/system.net/filewebrequest/begingetresponse/
---
## FileWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) متد

یک درخواست ناهمزمان برای منبع را آغاز می‌کند.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | یک کال‌بک که پس از تکمیل عملیات فراخوانی می‌شود. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | داده‌های فراهم‌شده توسط کاربر که برای شناسایی یکتای هر عملیات ناهمزمان استفاده می‌شود. |

### مقدار بازگشتی

یک شیء [IAsyncResult](../../../system/iasyncresult/) که نمایانگر عملیات ناهمزمان آغاز شده است.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [FileWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)