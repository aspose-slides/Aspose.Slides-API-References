---
title: BeginSend()
second_title: Aspose.Slides لـ C++ مرجع API
description: يبدأ عملية إرسال غير متزامنة.
type: docs
weight: 495
url: /ar/system.net.sockets/socket/beginsend/
---
## Socket::BeginSend(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) طريقة

يبدأ عملية إرسال غير متزامنة.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginSend(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مخزن مؤقت لقراءة البيانات منه. |
| offset | **int32_t** | الإزاحة بوحدات البايت في المصفوفة المحددة. |
| size | **int32_t** | عدد البايتات في المصفوفة المحددة بدءًا من المعامل 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الإرسال. |
| callback | [AsyncCallback](../../../system/asynccallback/) | دالة رد نداء سيتم استدعاؤها عند إكمال العملية. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | بيانات يقدمها المستخدم تُستخدم لتحديد كل عملية إرسال غير متزامنة بشكل فريد. |

### قيمة الإرجاع

كائن [IAsyncResult](../../../system/iasyncresult/) يمثل عملية الإرسال غير المتزامنة التي تم البدء بها.

## انظر أيضا

* تعداد [SocketFlags](../../socketflags/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [AsyncCallback](../../../system/asynccallback/)
* فئة [IAsyncResult](../../../system/iasyncresult/)
* فئة [Object](../../../system/object/)
* فئة [Socket](../)
* مساحة اسم [System::Net::Sockets](../../)
* مكتبة [Aspose.Slides](../../../)