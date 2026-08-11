---
title: BeginRead()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يبدأ عملية قراءة غير متزامنة.
type: docs
weight: 248
url: /ar/system.net.sockets/networkstream/beginread/
---
## NetworkStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) طريقة

يبدأ عملية قراءة غير متزامنة.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مصفوفة البايتات التي سيتم كتابة البايتات المقروءة فيها. |
| offset | **int32_t** | الإزاحة بالبايتات في المصفوفة المحددة. |
| size | **int32_t** | عدد البايتات المراد قراءتها. |
| callback | [AsyncCallback](../../../system/asynccallback/) | دالة رد نداء تُستدعى عند إكمال العملية. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | بيانات قدمها المستخدم تُستخدم لتحديد كل عملية قراءة غير متزامنة بشكل فريد. |

### قيمة الإرجاع

كائن [IAsyncResult](../../../system/iasyncresult/) يمثل عملية القراءة غير المتزامنة التي تم بدءها.

## انظر أيضاً

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* فئة [IAsyncResult](../../../system/iasyncresult/)
* فئة [Object](../../../system/object/)
* فئة [NetworkStream](../)
* نطاق [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)