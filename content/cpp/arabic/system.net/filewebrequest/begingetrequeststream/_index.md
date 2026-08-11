---
title: BeginGetRequestStream()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يبدأ عملية غير متزامنة للحصول على تدفق لكتابة البيانات إلى المورد.
type: docs
weight: 144
url: /ar/system.net/filewebrequest/begingetrequeststream/
---
## FileWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) طريقة

يبدأ عملية غير متزامنة للحصول على تدفق لكتابة البيانات إلى المورد.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | دالة استدعاء تُستدعى عند إكمال العملية. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | بيانات يوفرها المستخدم تُستخدم لتحديد كل عملية غير متزامنة بشكل فريد. |

### قيمة الإرجاع

كائن [IAsyncResult](../../../system/iasyncresult/) يمثل العملية غير المتزامنة التي بدأتها.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [AsyncCallback](../../../system/asynccallback/)
* صنف [IAsyncResult](../../../system/iasyncresult/)
* صنف [Object](../../../system/object/)
* صنف [FileWebRequest](../)
* نطاق [System::Net](../../)
* مكتبة [Aspose.Slides](../../../)