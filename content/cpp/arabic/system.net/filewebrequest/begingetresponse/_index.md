---
title: BeginGetResponse()
second_title: Aspose.Slides لـ C++ مرجع API
description: يبدء طلبًا غير متزامن للمورد.
type: docs
weight: 170
url: /ar/system.net/filewebrequest/begingetresponse/
---
## FileWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) طريقة


يبدأ طلبًا غير متزامن للمورد.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | استدعاء يُستدعى عند إكمال العملية. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | بيانات مقدمة من المستخدم تُستخدم لتحديد كل عملية غير متزامنة بشكل فريد. |

### قيمة الإرجاع

كائن [IAsyncResult](../../../system/iasyncresult/) يمثل العملية غير المتزامنة التي تم بدءها.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* فئة [IAsyncResult](../../../system/iasyncresult/)
* فئة [Object](../../../system/object/)
* فئة [FileWebRequest](../)
* مساحة الأسماء [System::Net](../../)
* Library [Aspose.Slides](../../../)