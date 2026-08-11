---
title: BeginGetRequestStream()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides لـ C++
description: يبدأ عملية غير متزامنة للحصول على تدفق من أجل كتابة البيانات إلى المورد.
type: docs
weight: 469
url: /ar/system.net/httpwebrequest/begingetrequeststream/
---
## HttpWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) طريقة


يبدأ عملية غير متزامنة للحصول على تدفق لكتابة البيانات إلى المورد.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | دالة رد نداء يتم استدعاؤها عند إكمال العملية. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | بيانات يقدمها المستخدم تُستخدم لتحديد كل عملية غير متزامنة بشكل فريد. |

### قيمة الإرجاع

كائن [IAsyncResult](../../../system/iasyncresult/) يمثل العملية غير المتزامنة التي تم بدءها.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* فئة [IAsyncResult](../../../system/iasyncresult/)
* فئة [Object](../../../system/object/)
* فئة [HttpWebRequest](../)
* مساحة الاسم [System::Net](../../)
* مكتبة [Aspose.Slides](../../../)