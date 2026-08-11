---
title: BeginResolve()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يبدأ عملية غير متزامنة لإنشاء مثيل جديد من الفئة IPHostEntry باستخدام اسم المضيف المحدد.
type: docs
weight: 157
url: /ar/system.net/dns/beginresolve/
---
## Dns::BeginResolve(String, AsyncCallback, System::SharedPtr\<Object\>) الطريقة

يبادر بعملية غير متزامنة لإنشاء مثيل جديد من الفئة IPHostEntry باستخدام اسم المضيف المحدد.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginResolve(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | اسم مضيف يُستخدم لإنشاء مثيل جديد من الفئة [IPHostEntry](../../iphostentry/). |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | دالة رد اتصال تُستدعى عندما تكتمل العملية. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | بيانات يقدمها المستخدم تُستخدم لتحديد كل عملية غير متزامنة بصورة فريدة. |

### قيمة الإرجاع

كائن [IAsyncResult](../../../system/iasyncresult/) يمثل العملية غير المتزامنة التي تم بدءها.

## انظر أيضًا

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* تعريف النوع [AsyncCallback](../../../system/asynccallback/)
* الفئة [IAsyncResult](../../../system/iasyncresult/)
* الفئة [String](../../../system/string/)
* الفئة [Object](../../../system/object/)
* الفئة [Dns](../)
* النطاق [System::Net](../../)
* المكتبة [Aspose.Slides](../../../)