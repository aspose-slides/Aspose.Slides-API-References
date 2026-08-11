---
title: BeginWrite()
second_title: Aspose.Slides لـ C++ مرجع API
description: يبدأ عملية كتابة غير متزامنة.
type: docs
weight: 274
url: /ar/system.net.sockets/networkstream/beginwrite/
---
## NetworkStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) طريقة

يبدأ عملية كتابة غير متزامنة.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مخزن مؤقت يحتوي على البيانات التي سيتم كتابتها. |
| offset | **int32_t** | الإزاحة بالبايت في المصفوفة المحددة. |
| size | **int32_t** | عدد البايتات التي يجب كتابتها. |
| callback | [AsyncCallback](../../../system/asynccallback/) | دالة رد نداء تُستدعى عند إكمال العملية. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | بيانات مقدمة من المستخدم تُستخدم لتحديد كل عملية كتابة غير متزامنة بشكل فريد. |

### قيمة الإرجاع

كائن [IAsyncResult](../../../system/iasyncresult/) يمثل عملية الكتابة غير المتزامنة التي تم بدءها.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [AsyncCallback](../../../system/asynccallback/)
* فئة [IAsyncResult](../../../system/iasyncresult/)
* فئة [Object](../../../system/object/)
* فئة [NetworkStream](../)
* نطاق [System::Net::Sockets](../../)
* مكتبة [Aspose.Slides](../../../)