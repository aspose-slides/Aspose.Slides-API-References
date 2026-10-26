---
title: BeginGetHostAddresses()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يبدأ عملية غير متزامنة لإنشاء كائن جديد من الفئة IPHostEntry-class باستخدام السلسلة المحددة التي تحتوي على اسم مضيف أو عنوان IP.
type: docs
weight: 131
url: /ar/system.net/dns/begingethostaddresses/
---
## Dns::BeginGetHostAddresses(String, AsyncCallback, System::SharedPtr\<Object\>) طريقة

يبدأ عملية غير متزامنة لإنشاء كائن جديد من فئة IPHostEntry-class باستخدام السلسلة المحددة التي تحتوي على اسم مضيف أو عنوان IP.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostAddresses(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | سلسلة تحتوي على اسم مضيف أو عنوان IP. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | دالة رد نداء تُستدعى عندما تكتمل العملية. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | بيانات مقدمة من المستخدم تُستخدم لتحديد كل عملية غير متزامنة بشكل فريد. |

### قيمة الإرجاع

كائن من نوع [IAsyncResult](../../../system/iasyncresult/) يمثل العملية غير المتزامنة التي تم بدءها.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* فئة [IAsyncResult](../../../system/iasyncresult/)
* فئة [String](../../../system/string/)
* فئة [Object](../../../system/object/)
* فئة [Dns](../)
* نطاق [System::Net](../../)
* مكتبة [Aspose.Slides](../../../)