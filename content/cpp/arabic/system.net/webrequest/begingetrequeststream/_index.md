---
title: BeginGetRequestStream()
second_title: مرجع API Aspose.Slides للغة C++
description: يباشر عملية غير متزامنة للحصول على تدفق لكتابة البيانات إلى المورد.
type: docs
weight: 300
url: /ar/system.net/webrequest/begingetrequeststream/
---
## WebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) الطريقة

يباشر عملية غير متزامنة للحصول على تدفق لكتابة البيانات إلى المورد.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | دالة رد نداء تُستدعى عند انتهاء العملية. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | بيانات يقدمها المستخدم تُستخدم لتحديد كل عملية غير متزامنة بشكل فريد. |

## قيمة الإرجاع

كائن [IAsyncResult](../../../system/iasyncresult/) يمثل العملية غير المتزامنة التي تم بدءها.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [AsyncCallback](../../../system/asynccallback/)
* الفئة [IAsyncResult](../../../system/iasyncresult/)
* الفئة [Object](../../../system/object/)
* الفئة [WebRequest](../)
* فضاء الاسم [System::Net](../../)
* المكتبة [Aspose.Slides](../../../)