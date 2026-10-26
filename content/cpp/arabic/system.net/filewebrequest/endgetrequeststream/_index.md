---
title: EndGetRequestStream()
second_title: مرجع API Aspose.Slides للغة C++
description: ينتظر حتى يكتمل العملية غير المتزامنة المحددة للحصول على تدفق.
type: docs
weight: 157
url: /ar/system.net/filewebrequest/endgetrequeststream/
---
## FileWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) طريقة

ينتظر حتى يكتمل العملية غير المتزامنة المحددة للحصول على تدفق.

```cpp
System::SharedPtr<IO::Stream> System::Net::FileWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | كائن [IAsyncResult](../../../system/iasyncresult/) يمثل عملية غير متزامنة للحصول على تدفق. |

### قيمة الإرجاع

التدفق لكتابة البيانات إلى المورد.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Stream](../../../system.io/stream/)
* فئة [IAsyncResult](../../../system/iasyncresult/)
* فئة [FileWebRequest](../)
* نطاق [System::Net](../../)
* مكتبة [Aspose.Slides](../../../)