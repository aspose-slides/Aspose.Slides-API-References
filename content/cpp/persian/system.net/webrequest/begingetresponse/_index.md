---
title: BeginGetResponse()
second_title: مرجع API Aspose.Slides برای C++
description: درخواست ناهمزمانی برای منبع را آغاز می‌کند.
type: docs
weight: 274
url: /fa/system.net/webrequest/begingetresponse/
---
## WebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) متد

یک درخواست ناهمزمان برای منبع را آغاز می‌کند.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | یک کال-بک که پس از تکمیل عملیات فراخوانی می‌شود. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | داده‌ای که توسط کاربر فراهم شده و برای شناسایی یکتا هر عملیات ناهمزمان استفاده می‌شود. |

### مقدار بازگشت

یک [IAsyncResult](../../../system/iasyncresult/) شیء که نمایانگر عملیات ناهمزمان آغاز شده است.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* کلاس [IAsyncResult](../../../system/iasyncresult/)
* کلاس [Object](../../../system/object/)
* کلاس [WebRequest](../)
* فضای نام [System::Net](../../)
* Library [Aspose.Slides](../../../)