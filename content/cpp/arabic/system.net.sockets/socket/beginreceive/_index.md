---
title: BeginReceive()
second_title: Aspose.Slides لـ C++ مرجع API
description: يبدأ عملية كتابة غير متزامنة.
type: docs
weight: 521
url: /ar/system.net.sockets/socket/beginreceive/
---
## Socket::BeginReceive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) طريقة

يُشغِّل عملية كتابة غير تزامنية.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginReceive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | المخزن buffer حيث سيتم تعيين البيانات المستلمة. |
| offset | **int32_t** | الإزاحة offset بالبايتات في المصفوفة المحددة. |
| size | **int32_t** | عدد البايتات في المصفوفة المحددة بدءًا من المعامل 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | سلوك الاستلام socketFlags. |
| callback | [AsyncCallback](../../../system/asynccallback/) | دالة رد الاتصال callback التي سيتم استدعاؤها عند إكمال العملية. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | البيانات التي يزوّدها المستخدم state والتي تُستخدم لتحديد كل عملية استلام غير تزامنية بشكل فريد. |

### قيمة الإرجاع

كائن [IAsyncResult](../../../system/iasyncresult/) يمثل عملية الاستلام غير المتزامنة المُبادَرة.

## انظر أيضًا

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)