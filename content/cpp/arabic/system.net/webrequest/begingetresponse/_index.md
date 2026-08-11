---
title: BeginGetResponse()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يُطلق طلبًا غير متزامن للمورد.
type: docs
weight: 274
url: /ar/system.net/webrequest/begingetresponse/
---
## WebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) طريقة

يُطلق طلبًا غير متزامن للمورد.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | دالة رد نداء تُستدعى عند اكتمال العملية. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | بيانات مقدمة من المستخدم تُستخدم لتحديد كل عملية غير متزامنة بشكل فريد. |

### قيمة الإرجاع

كائن [IAsyncResult](../../../system/iasyncresult/) يمثل العملية غير المتزامنة التي تم بدءها.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [AsyncCallback](../../../system/asynccallback/)
* فئة [IAsyncResult](../../../system/iasyncresult/)
* فئة [Object](../../../system/object/)
* فئة [WebRequest](../)
* نطاق [System::Net](../../)
* مكتبة [Aspose.Slides](../../../)