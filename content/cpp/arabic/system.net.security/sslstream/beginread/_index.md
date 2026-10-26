---
title: BeginRead()
second_title: مرجع API Aspose.Slides للغة C++
description: يبدأ عملية قراءة غير متزامنة.
type: docs
weight: 417
url: /ar/system.net.security/sslstream/beginread/
---
## SslStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method


Initiates an asynchronous read operation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```


### المعامل

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مصفوفة البايت لقراءة البيانات منها. |
| offset | **int32_t** | الإزاحة بالبايتات في المصفوفة المحددة. |
| count | **int32_t** | عدد البايتات التي سيتم قراءتها. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | دالة رد نداء تُستدعى عند اكتمال العملية. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | بيانات يقدمها المستخدم تُستخدم لتحديد كل عملية قراءة غير متزامنة بصورة فريدة. |

### قيمة الإرجاع

كائن [IAsyncResult](../../../system/iasyncresult/) يمثل عملية القراءة غير المتزامنة التي تم بدءها.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* الفئة [IAsyncResult](../../../system/iasyncresult/)
* الفئة [Object](../../../system/object/)
* الفئة [SslStream](../)
* النطاق [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)