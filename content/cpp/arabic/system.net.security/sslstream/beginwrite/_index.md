---
title: BeginWrite()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يباشر عملية كتابة غير متزامنة.
type: docs
weight: 443
url: /ar/system.net.security/sslstream/beginwrite/
---
## SslStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) طريقة

يباشر عملية كتابة غير متزامنة.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مصفوفة البايت التي تُكتب البيانات إليها. |
| offset | **int32_t** | الإزاحة بالبايت في المصفوفة المحددة. |
| count | **int32_t** | عدد البايتات للكتابة. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | دالة استرجاع تُستدعى عند إكمال العملية. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | بيانات يقدمها المستخدم تُستخدم لتحديد كل عملية كتابة غير متزامنة بشكل فريد. |

### قيمة الإرجاع

كائن [IAsyncResult](../../../system/iasyncresult/) يمثل عملية الكتابة غير المتزامنة التي تم بدءها.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [AsyncCallback](../../../system/asynccallback/)
* فئة [IAsyncResult](../../../system/iasyncresult/)
* فئة [Object](../../../system/object/)
* فئة [SslStream](../)
* نطاق [System::Net::Security](../../)
* مكتبة [Aspose.Slides](../../../)