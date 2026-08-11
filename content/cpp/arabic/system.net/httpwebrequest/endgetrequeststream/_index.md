---
title: EndGetRequestStream()
second_title: مرجع API Aspose.Slides للغة C++
description: يتنّظر حتى تكتمل العملية غير المتزامنة المحددة للحصول على تدفق.
type: docs
weight: 482
url: /ar/system.net/httpwebrequest/endgetrequeststream/
---
## HttpWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) طريقة

ينتظر حتى تكتمل العملية غير المتزامنة المحددة للحصول على تدفق.

```cpp
System::SharedPtr<IO::Stream> System::Net::HttpWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | كائن [IAsyncResult](../../../system/iasyncresult/) يمثل عملية غير متزامنة للحصول على تدفق. |

### قيمة الإرجاع

التدفق لكتابة البيانات إلى المورد.

## انظر أيضا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Stream](../../../system.io/stream/)
* فئة [IAsyncResult](../../../system/iasyncresult/)
* فئة [HttpWebRequest](../)
* مساحة الأسماء [System::Net](../../)
* مكتبة [Aspose.Slides](../../../)