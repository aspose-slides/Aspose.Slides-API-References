---
title: EndReceive()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: ينتظر حتى تكتمل عملية الاستقبال غير المتزامنة المحددة.
type: docs
weight: 534
url: /ar/system.net.sockets/socket/endreceive/
---
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>) طريقة

ينتظر حتى تكتمل عملية الاستقبال غير المتزامنة المحددة.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | كائن [IAsyncResult](../../../system/iasyncresult/) يمثل عملية استقبال غير متزامنة. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>, SocketError\&) طريقة

ينتظر حتى تكتمل عملية الاستقبال غير المتزامنة المحددة.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | كائن [IAsyncResult](../../../system/iasyncresult/) يمثل عملية استقبال غير متزامنة. |
| errorCode | [SocketError](../../socketerror/)\& | معامل الإخراج الذي سيتم تعيين رمز الخطأ فيه عندما تفشل عملية الاستقبال. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## See Also

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)