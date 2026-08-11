---
title: EndSend()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينتظر حتى تكتمل عملية الإرسال غير المتزامنة المحددة.
type: docs
weight: 508
url: /ar/system.net.sockets/socket/endsend/
---
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>) طريقة

ينتظر حتى تكتمل عملية الإرسال غير المتزامنة المحددة.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult)
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | كائن [IAsyncResult](../../../system/iasyncresult/) يمثل عملية إرسال غير متزامنة. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## Socket::EndSend(System::SharedPtr\<IAsyncResult\>, SocketError\&) طريقة

ينتظر حتى تكتمل عملية الإرسال غير المتزامنة المحددة.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | كائن [IAsyncResult](../../../system/iasyncresult/) يمثل عملية إرسال غير متزامنة. |
| errorCode | [SocketError](../../socketerror/)\& | معامل الإخراج الذي سيتم تعيين رمز الخطأ فيه عندما تفشل عملية الإرسال. |

### قيمة الإرجاع

عدد البايتات المرسلة.

## انظر أيضًا

* تعداد [SocketError](../../socketerror/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IAsyncResult](../../../system/iasyncresult/)
* فئة [Socket](../)
* مساحة اسم [System::Net::Sockets](../../)
* مكتبة [Aspose.Slides](../../../)