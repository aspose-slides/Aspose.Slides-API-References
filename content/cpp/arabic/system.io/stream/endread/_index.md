---
title: EndRead()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينتظر حتى تكتمل عملية القراءة غير المتزامنة المحددة.
type: docs
weight: 183
url: /ar/system.io/stream/endread/
---
## Stream::EndRead(System::SharedPtr\<System::IAsyncResult\>) طريقة

ينتظر حتى تكتمل عملية القراءة غير المتزامنة المحددة.

```cpp
virtual int System::IO::Stream::EndRead(System::SharedPtr<System::IAsyncResult> asyncResult)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[System::IAsyncResult](../../../system/iasyncresult/)\> | كائن [IAsyncResult](../../../system/iasyncresult/) يمثل عملية قراءة غير متزامنة |

### قيمة الإرجاع

عدد البايتات المقروءة أثناء عملية القراءة التي يمثلها **asyncResult**

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IAsyncResult](../../../system/iasyncresult/)
* فئة [Stream](../)
* نطاق [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)