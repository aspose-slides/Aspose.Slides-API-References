---
title: EndGetRequestStream()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينتظر حتى تكتمل العملية غير المتزامنة المحددة للحصول على تدفق.
type: docs
weight: 313
url: /ar/system.net/webrequest/endgetrequeststream/
---
## WebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) طريقة

ينتظر حتى تُستكمل العملية غير المتزامنة المحددة للحصول على تدفق.

```cpp
virtual System::SharedPtr<IO::Stream> System::Net::WebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult)=0
```

### المعلمات

| معـامل | نوع | وصف |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | كائن [IAsyncResult](../../../system/iasyncresult/) يمثل عملية غير متزامنة للحصول على تدفق. |

### قيمة الإرجاع

التدفق لكتابة البيانات إلى المورد.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [Stream](../../../system.io/stream/)
* فئة [IAsyncResult](../../../system/iasyncresult/)
* فئة [WebRequest](../)
* نطاق [System::Net](../../)
* مكتبة [Aspose.Slides](../../../)