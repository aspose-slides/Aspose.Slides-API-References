---
title: BeginGetHostEntry()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يبدأ عملية غير متزامنة لإنشاء نسخة جديدة من فئة IPHostEntry-class باستخدام السلسلة المحددة التي تحتوي على اسم مضيف أو عنوان IP.
type: docs
weight: 105
url: /ar/system.net/dns/begingethostentry/
---
## Dns::BeginGetHostEntry(String, AsyncCallback, System::SharedPtr\<Object\>) طريقة

يبدأ عملية غير متزامنة لإنشاء كائن من فئة IPHostEntry-class باستخدام السلسلة المحددة التي تحتوي على اسم مضيف أو عنوان IP.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | السلسلة التي تحتوي على اسم مضيف أو عنوان IP. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | رد نداء يتم استدعاؤه عند انتهاء العملية. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | بيانات مقدمة من المستخدم تُستخدم لتحديد كل عملية غير متزامنة بشكل فريد. |

### قيمة الإرجاع

كائن [IAsyncResult](../../../system/iasyncresult/) يمثل العملية غير المتزامنة التي تم بدءها.

## Dns::BeginGetHostEntry(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) طريقة

يبدأ عملية غير متزامنة لإنشاء كائن من فئة IPHostEntry-class باستخدام عنوان IP المحدد.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(System::SharedPtr<IPAddress> address, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | عنوان IP. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | رد نداء يتم استدعاؤه عند انتهاء العملية. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | بيانات مقدمة من المستخدم تُستخدم لتحديد كل عملية غير متزامنة بشكل فريد. |

### قيمة الإرجاع

كائن [IAsyncResult](../../../system/iasyncresult/) يمثل العملية غير المتزامنة التي تم بدءها.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* فئة [IAsyncResult](../../../system/iasyncresult/)
* فئة [String](../../../system/string/)
* فئة [Object](../../../system/object/)
* فئة [Dns](../)
* فئة [IPAddress](../../ipaddress/)
* مساحة الأسماء [System::Net](../../)
* مكتبة [Aspose.Slides](../../../)