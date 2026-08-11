---
title: BeginGetHostByName()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يُنشئ عملية غير متزامنة لإنشاء مثال جديد من الفئة IPHostEntry باستخدام اسم المضيف المحدد.
type: docs
weight: 53
url: /ar/system.net/dns/begingethostbyname/
---
## Dns::BeginGetHostByName(String, AsyncCallback, System::SharedPtr\<Object\>) طريقة

يُنشئ عملية غير متزامنة لإنشاء مثال جديد من الفئة IPHostEntry باستخدام اسم المضيف المحدد.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostByName(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | اسم مضيف. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | دالة رد نداء تُستدعى عند إكمال العملية. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | بيانات مقدمة من المستخدم تُستخدم لتحديد كل عملية غير متزامنة بصورة فريدة. |

### قيمة الإرجاع

كائن [IAsyncResult](../../../system/iasyncresult/) يمثل العملية غير المتزامنة التي تم بدءها.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)