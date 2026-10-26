---
title: EndRead()
second_title: مرجع API Aspose.Slides للغة C++
description: ينتظر حتى تكتمل عملية القراءة غير المتزامنة المحددة.
type: docs
weight: 261
url: /ar/system.net.sockets/networkstream/endread/
---
## NetworkStream::EndRead(System::SharedPtr\<IAsyncResult\>) طريقة

ينتظر حتى تكتمل عملية القراءة غير المتزامنة المحددة.

```cpp
int32_t System::Net::Sockets::NetworkStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | كائن [IAsyncResult](../../../system/iasyncresult/) يمثل عملية قراءة غير متزامنة |

### قيمة الإرجاع

عدد البايتات التي تم قراءتها أثناء عملية القراءة التي يمثلها **asyncResult**

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IAsyncResult](../../../system/iasyncresult/)
* فئة [NetworkStream](../)
* نطاق [System::Net::Sockets](../../)
* مكتبة [Aspose.Slides](../../../)