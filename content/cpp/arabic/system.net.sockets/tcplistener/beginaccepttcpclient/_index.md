---
title: BeginAcceptTcpClient()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يبدأ عملية قبول غير متزامنة.
type: docs
weight: 170
url: /ar/system.net.sockets/tcplistener/beginaccepttcpclient/
---
## TcpListener::BeginAcceptTcpClient(AsyncCallback, System::SharedPtr\<Object\>) طريقة

يبدأ عملية قبول غير متزامنة.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptTcpClient(AsyncCallback callback, System::SharedPtr<Object> state)
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | دالة رد نداء سيتم استدعاؤها عندما تكتمل العملية. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | بيانات يقدمها المستخدم تُستخدم لتمييز كل عملية اتصال غير متزامنة بشكل فريد. |

### قيمة الإرجاع

كائن [IAsyncResult](../../../system/iasyncresult/) يمثل عملية القبول غير المتزامنة التي تم بدءها.

## أنظر أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [AsyncCallback](../../../system/asynccallback/)
* فئة [IAsyncResult](../../../system/iasyncresult/)
* فئة [Object](../../../system/object/)
* فئة [TcpListener](../)
* مساحة الاسم [System::Net::Sockets](../../)
* مكتبة [Aspose.Slides](../../../)